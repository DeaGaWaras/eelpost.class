<script>
export default {
  data() {
    return {
      activeTab: 1,
      tech: [
        {
          id: 1,
          name: 'Fisika',
          imageUrl: 'https://telegra.ph/file/23abb61f5528d24b82b7b.png',
          status: 'Peminatan'
        },
        {
          id: 2,
          name: 'Biologi',
          imageUrl: 'https://telegra.ph/file/23abb61f5528d24b82b7b.png',
          status: 'Peminatan'
        },
        {
          id: 3,
          name: 'Kimia',
          imageUrl: 'https://telegra.ph/file/23abb61f5528d24b82b7b.png',
          status: 'Peminatan'
        },
        {
          id: 4,
          name: 'Infomatika',
          imageUrl: 'https://telegra.ph/file/23abb61f5528d24b82b7b.png',
          status: 'Peminatan'
        },
        {
          id: 5,
          name: 'Matematika',
          imageUrl: 'https://telegra.ph/file/23abb61f5528d24b82b7b.png',
          status: 'Umum'
        },
        {
          id: 6,
          name: 'Bhs. Indonesia',
          imageUrl: 'https://telegra.ph/file/23abb61f5528d24b82b7b.png',
          status: 'Umum'
        },
        {
          id: 7,
          name: 'Agama',
          imageUrl: 'https://telegra.ph/file/23abb61f5528d24b82b7b.png',
          status: 'Umum'
        },
        {
          id: 8,
          name: 'Seni Budaya',
          imageUrl: 'https://telegra.ph/file/23abb61f5528d24b82b7b.png',
          status: 'Umum'
        },
        {
          id: 9,
          name: 'Sejarah',
          imageUrl: 'https://telegra.ph/file/23abb61f5528d24b82b7b.png',
          status: 'Umum'
        },
        {
          id: 10,
          name: 'Olahraga',
          imageUrl: 'https://telegra.ph/file/23abb61f5528d24b82b7b.png',
          status: 'Umum'
        },
        {
          id: 11,
          name: 'Pancasila',
          imageUrl: 'https://telegra.ph/file/23abb61f5528d24b82b7b.png',
          status: 'Umum'
        },
        {
          id: 12,
          name: 'Prakarya',
          imageUrl: 'https://telegra.ph/file/23abb61f5528d24b82b7b.png',
          status: 'Umum'
        }
      ],
      Student: [
        {
          id: 1,
          name: 'Absen 1',
          imageUrl: 'https://telegra.ph/file/0de698bd9a77951fceb19.png',
          status: 'Aditya Eko P'
        },
        {
          id: 2,
          name: 'Absen 2',
          imageUrl: 'https://telegra.ph/file/1c7731027771352c4f20f.png',
          status: 'Alfrinda Melvi A.P'
        },
        {
          id: 3,
          name: 'Absen 3',
          imageUrl: 'https://telegra.ph/file/0de698bd9a77951fceb19.png',
          status: 'Anggita Nova D.N'
        },
        {
          id: 4,
          name: 'Absen 4',
          imageUrl: 'https://telegra.ph/file/1c7731027771352c4f20f.png',
          status: 'Apri Nayla S.T'
        },
        {
          id: 5,
          name: 'Absen 5',
          imageUrl: 'https://telegra.ph/file/0de698bd9a77951fceb19.png',
          status: 'Ariska Kurnia P'
        },
        {
          id: 6,
          name: 'Absen 6',
          imageUrl: 'https://telegra.ph/file/1c7731027771352c4f20f.png',
          status: 'Ayoedya Putri H'
        },
        {
          id: 7,
          name: 'Absen 7',
          imageUrl: 'https://telegra.ph/file/1c7731027771352c4f20f.png',
          status: 'Azizahra Wahyu K'
        },
        {
          id: 8,
          name: 'Absen 8',
          imageUrl: 'https://telegra.ph/file/0de698bd9a77951fceb19.png',
          status: 'Bayu Guyuh U'
        },
        {
          id: 9,
          name: 'Absen 9',
          imageUrl: 'https://telegra.ph/file/1c7731027771352c4f20f.png',
          status: 'Candy Vebri A.K'
        },
        {
          id: 10,
          name: 'Absen 10',
          imageUrl: 'https://telegra.ph/file/1c7731027771352c4f20f.png',
          status: 'Chetty A'
        },
        {
          id: 11,
          name: 'Absen 11',
          imageUrl: 'https://telegra.ph/file/0de698bd9a77951fceb19.png',
          status: 'Dava Tristian A'
        },
        {
          id: 12,
          name: 'Absen 12',
          imageUrl: 'https://telegra.ph/file/0de698bd9a77951fceb19.png',
          status: 'Denny Satria A'
        },
        {
          id: 13,
          name: 'Absen 13',
          imageUrl: 'https://telegra.ph/file/0de698bd9a77951fceb19.png',
          status: 'Devika Aditiyansa'
        },
        {
          id: 14,
          name: 'Absen 14',
          imageUrl: 'https://telegra.ph/file/1c7731027771352c4f20f.png',
          status: 'Exti Nola V'
        },
        {
          id: 15,
          name: 'Absen 15',
          imageUrl: 'https://telegra.ph/file/0de698bd9a77951fceb19.png',
          status: 'Farez Rahmansya'
        },
        {
          id: 16,
          name: 'Absen 16',
          imageUrl: 'https://telegra.ph/file/0de698bd9a77951fceb19.png',
          status: 'Fauzan A. Putra'
        },
        {
          id: 17,
          name: 'Absen 17',
          imageUrl: 'https://telegra.ph/file/1c7731027771352c4f20f.png',
          status: 'Ghefira Afrilia V'
        },
        {
          id: 18,
          name: 'Absen 18',
          imageUrl: 'https://telegra.ph/file/1c7731027771352c4f20f.png',
          status: 'Ghian Ellischa I.S'
        },
        {
          id: 19,
          name: 'Absen 19',
          imageUrl: 'https://telegra.ph/file/0de698bd9a77951fceb19.png',
          status: 'Leonardo Hardika'
        },
        {
          id: 20,
          name: 'Absen 20',
          imageUrl: 'https://telegra.ph/file/0de698bd9a77951fceb19.png',
          status: 'Lukman Hakim'
        },
        {
          id: 21,
          name: 'Absen 21',
          imageUrl: 'https://telegra.ph/file/1c7731027771352c4f20f.png',
          status: 'Mafika C. Cahyani'
        },
        {
          id: 22,
          name: 'Absen 22',
          imageUrl: 'https://telegra.ph/file/0de698bd9a77951fceb19.png',
          status: 'Maulana Ainul Y'
        },
        {
          id: 23,
          name: 'Absen 23',
          imageUrl: 'https://telegra.ph/file/1c7731027771352c4f20f.png',
          status: 'Michelle Cherish B'
        },
        {
          id: 24,
          name: 'Absen 24',
          imageUrl: 'https://telegra.ph/file/1c7731027771352c4f20f.png',
          status: 'Nabilla Okte F'
        },
        {
          id: 25,
          name: 'Absen 25',
          imageUrl: 'https://telegra.ph/file/1c7731027771352c4f20f.png',
          status: 'Nadyna A. Tyas'
        },
        {
          id: 26,
          name: 'Absen 26',
          imageUrl: 'https://telegra.ph/file/1c7731027771352c4f20f.png',
          status: 'Novita Sri Utami'
        },
        {
          id: 27,
          name: 'Absen 27',
          imageUrl: 'https://telegra.ph/file/0de698bd9a77951fceb19.png',
          status: 'Panji Angga S'
        },
        {
          id: 28,
          name: 'Absen 28',
          imageUrl: 'https://telegra.ph/file/0de698bd9a77951fceb19.png',
          status: 'Rayendra Hafizh I.H'
        },
        {
          id: 29,
          name: 'Absen 29',
          imageUrl: 'https://telegra.ph/file/0de698bd9a77951fceb19.png',
          status: 'Ridho Kurnia R'
        },
        {
          id: 30,
          name: 'Absen 30',
          imageUrl: 'https://telegra.ph/file/0de698bd9a77951fceb19.png',
          status: 'Rizki Dwi Wahyu P'
        },
        {
          id: 31,
          name: 'Absen 31',
          imageUrl: 'https://telegra.ph/file/0de698bd9a77951fceb19.png',
          status: 'Royan Aji Kusuma'
        },
        {
          id: 32,
          name: 'Absen 32',
          imageUrl: 'https://telegra.ph/file/0de698bd9a77951fceb19.png',
          status: 'Rozzaq Alfian Fauzi'
        },
        {
          id: 33,
          name: 'Absen 33',
          imageUrl: 'https://telegra.ph/file/0de698bd9a77951fceb19.png',
          status: 'Satria Ananda B'
        },
        {
          id: 34,
          name: 'Absen 34',
          imageUrl: 'https://telegra.ph/file/1c7731027771352c4f20f.png',
          status: 'Sinta Dwi Safitri'
        },
        {
          id: 35,
          name: 'Absen 35',
          imageUrl: 'https://telegra.ph/file/0de698bd9a77951fceb19.png',
          status: 'Syah Aradea A'
        },
        {
          id: 36,
          name: 'Absen 36',
          imageUrl: 'https://telegra.ph/file/1c7731027771352c4f20f.png',
          status: 'Syifa Dhenis Nafisa'
        },
      ],
    };
  }
}
</script>
<template>
  <div
    class="bg-[#1e1e1f] px-5 py-5 md:px-12 md:py-10 text-left border border-[#383838] rounded-3xl text-amber-50 mx-3 mb-5">
    <article data-page="about">

      <header>
        <div class="text-2xl font-bold text-white mb-5 fadein-bot title-section flex items-center">
          About We &nbsp;
          <div class="h-[1px] w-32 bg-amber-200 md:w-96 aos-init aos-animate" data-aos="zoom-in-left"
            data-aos-duration="600"></div>
        </div>
      </header>

      <section
        class="text-sm md:text-lg text-justify flex flex-col gap-4 md:flex-row md:gap-8 md:justify-left md:items-center">
        <div class="flex justify-center">
          <img class="w-9/12 rounded-full mb-3 fadein-up"
            src="https://telegra.ph/file/d3c449312a303ed1717c7.png" alt="Foto">
        </div>
        <div class="md:w-7/12">
          <p class="mb-3 md:mb-7 fadein-left fadeins-1">
            &nbsp; &nbsp; &nbsp; Halo semuanya!
Kami dari kelas XI-B asal SMAN 1 Kedunggalar, sebuah sekolah yang terletak di kota Ngawi, Jawa Timur, Indonesia.
Kami bangga dikenal sebagai "The Eelpost Class" – kelas yang penuh semangat dan kreativitas.

Di kelas kami, terdapat 36 individu luar biasa, terdiri dari 16 perempuan pintar dan 20 laki-laki tangguh. Bersama-sama, kami membentuk satu kesatuan yang solid dan harmonis. Kami beruntung memiliki Bu Wiwin S.Pd sebagai wali kelas kami,
seorang pendidik yang penuh inspirasi dan dedikasi.
          </p>
          <p class="mb-3 fadein-left fadeins-2">
            &nbsp; &nbsp; &nbsp; Dengan tekad dan kerja keras, tujuan utama kami adalah membawa nama baik SMAN 1 Kedunggalar ke puncak prestasi. Kami percaya bahwa dengan semangat kebersamaan dan usaha yang gigih, tidak ada yang tidak mungkin bagi kami.
Inilah kami, siap untuk menghadapi tantangan, meraih mimpi, dan mengukir prestasi!
          </p>
        </div>

      </section>

    </article>
  </div>

  <div class="px-5 py-5 md:px-12 md:py-10 text-left text-amber-50 mx-3">
    <article data-page="about">
      <header>
        <div class="text-2xl font-bold text-white mb-5 fadein-bot title-section flex items-center">
          <div class="h-[1px] w-10 bg-amber-200 md:w-20 aos-init aos-animate" data-aos="zoom-in-left"
            data-aos-duration="600"></div>
          &nbsp; Structure XI-B
        </div>
      </header>
      <section>
        <div>
          <ul class="flex flex-wrap text-sm font-medium text-center text-gray-500 dark:text-gray-400 mb-5">
            <li class="mr-2">
              <button class="inline-block px-4 py-3 rounded-lg hover:text-white"
                :class="{ 'text-amber-200 bg-amber-200 bg-opacity-10': activeTab === 1 }" @click="activeTab = 1">Learning</button>
            </li>
            <li class="mr-2">
              <button class="inline-block px-4 py-3 rounded-lg hover:text-white"
                :class="{ 'text-amber-200 bg-amber-200 bg-opacity-10': activeTab === 2 }" @click="activeTab = 2">Students</button>
            </li>
          </ul>
        </div>
        <div v-show="activeTab === 1">
          <div class="grid grid-cols-2 gap-4 pb-32 md:grid-cols-3 md:gap-8 xl:grid-cols-4 xl:gap-10 2xl:gap-12">
            <div v-for="item in tech" :key="item.id">
              <div
                class="item-tech flex cursor-pointer items-center gap-2 rounded border border-amber-200 px-2 py-2 hover:bg-amber-200 hover:bg-opacity-10 md:gap-3 lg:px-3">
                <div class="flex h-12 w-12 items-center justify-center p-0 lg:h-16 lg:w-16 lg:p-2 zoom-in">
                  <img alt="HTML" loading="lazy" width="32" height="32" decoding="async" data-nimg="1"
                    class="img-tech drop-shadow-xl transition-all duration-300 h-[65%] w-[65%] lg:h-[85%] lg:w-[85%]  "
                    :src="item.imageUrl" style="color: transparent;">
                </div>
                <div class="flex items-center text-sm md:text-base lg:text-lg">
                  <div class="tech font-medium text-secondary transition-all duration-300 translate-y-0 ">{{ item.name }}
                  </div>
                  <div
                    class="status-tech opacity-0 absolute mt-5 text-[10px] text-amber-200 transition-all duration-300 md:text-xs lg:text-sm">
                    {{ item.status }}</div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div v-show="activeTab === 2">
         <div class="grid grid-cols-2 gap-4 pb-32 md:grid-cols-3 md:gap-8 xl:grid-cols-4 xl:gap-10 2xl:gap-12">
          <div v-for="item in Student" :key="item.id">
           <div class="item-tech flex flex-col items-center gap-2 rounded border border-amber-200 px-3 py-2 hover:bg-amber-200 hover:bg-opacity-10">
            <div class="flex items-center justify-center p-0 h-16 w-16 lg:h-20 lg:w-20">
             <img alt="HTML" loading="lazy" width="64" height="64" decoding="async" class="img-tech drop-shadow-xl transition-all duration-300 h-[80%] w-[80%]"
            :src="item.imageUrl" style="color: transparent;">
              </div>
             <div class="flex flex-col items-center text-sm md:text-base lg:text-lg mt-2">
            <div class="tech font-medium text-secondary transition-all duration-300">{{ item.name }}</div>
            <div class="status-tech text-xs text-amber-200 mt-1 transition-all duration-300">
            {{ item.status }}
          </div>
         </div>
        </div>
       </div>
      </div>
    </div>
   
      </section>
    </article>
  </div>
</template>

<style>
.fadein-left {
  opacity: 0;
  animation: fadeInLeft 0.5s ease-out forwards;
}

@keyframes fadeInLeft {
  0% {
    opacity: 0;
    transform: translateX(100%);
  }

  100% {
    opacity: 1;
    transform: translateX(0);
  }
}

.fadeins-1 {
  animation-delay: 500ms;
}

.fadeins-2 {
  animation-delay: 800ms;
}

.img-tech,
.tech {
  transition: transform 0.3s ease;
}

.item-tech:hover .img-tech {
  transform: scale(1.3);
}

.item-tech:hover .tech {
  transform: translateY(-12px);
}

.item-tech:hover .status-tech {
  opacity: 1;
}
</style>
