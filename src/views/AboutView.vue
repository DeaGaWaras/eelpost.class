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
          name: 'Jasmani',
          imageUrl: 'https://telegra.ph/file/23abb61f5528d24b82b7b.png',
          status: 'Umum'
        },
        {
          id: 11,
          name: 'Kenegaraan',
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
      tools: [
        {
          id: 1,
          name: 'Ruang Kelas',
          imageUrl: 'https://telegra.ph/file/817f7c4534eaa1b12fae0.png',
          status: 'One For All'
        },
        {
          id: 2,
          name: 'Lab. Komputer',
          imageUrl: 'https://telegra.ph/file/1560751eb53c74c4079c4.png',
          status: 'Learn Programming'
        },
        {
          id: 3,
          name: 'Lab. IPA',
          imageUrl: 'https://telegra.ph/file/75e513348303c02b0b2e4.png',
          status: 'Experimental Learning'
        },
        {
          id: 4,
          name: 'Library',
          imageUrl: 'https://telegra.ph/file/8f85c3176350d6e3e542e.png',
          status: 'Place to Read Books'
        },
      ]
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
          &nbsp; Schedule XI-B
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
                :class="{ 'text-amber-200 bg-amber-200 bg-opacity-10': activeTab === 2 }" @click="activeTab = 2">Place</button>
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
            <div v-for="item in tools" :key="item.id">
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
