<template>
   <div class="w-full md:w-3/5 mx-auto md:mt-5 p-4">
        <div class="bg-white rounded-xl mx-3 p-5 md:p-10 md:mx-0 shadow-lg transition duration-300 ease-in-out transform hover:-translate-y-1 hover:shadow-2xl">
            <div v-for="(schedule, index) in schedules" :key="index" class="mb-8">
                <h1 class="text-lg md:text-3xl text-black text-left font-bold leading-relaxed">{{ schedule.jam }}</h1>
                <div class="mt-2 text-left text-gray-700 text-sm md:text-base">
                    <span>Schedule: <span class="font-semibold">{{ schedule.mataPelajaran }} </span></span>
                </div>
                 <div class="text-left text-black mt-5 md:mt-8 grid grid-cols-1 md:grid-cols-2 gap-4">
                    <p class="font-medium">Nama Pengajar: <span class="font-normal">{{ schedule.namaPengajar }}</span></p>
                    <p class="font-medium">Jam Pembelajaran: <span class="font-normal">{{ schedule.jamPembelajaran }}</span></p>
                </div>
                <div class="h-[2px] w-20 my-3 bg-[#ffdb70] rounded md:my-5 md:w-1/3"></div>
            </div>
        </div>
    </div>
</template>

<script>
import axios from 'axios';
import { useRoute } from 'vue-router';

export default {
    data() {
        return {
            route: useRoute(),
            schedules: []
        }
    },
    mounted() {
        this.getDetails();
    },
    methods: {
        async getDetails() {
            const id = this.$route.params.id;
            axios.get('https://66a37ebb44aa6370458168be.mockapi.io/api/memories/all/articles?id=' + id)
                .then(response => {
                    const articles = response.data;
                    articles.forEach(article => {
                        article.result.forEach(schedule => {
                            this.schedules.push({
                                mataPelajaran: schedule.mataPelajaran,
                                namaPengajar: schedule.namaPengajar,
                                jamPembelajaran: schedule.jamPembelajaran,
                                jam: schedule.waktu
                            });
                        });
                    });
                });
        }
    }
}
</script>

<style scoped></style>
