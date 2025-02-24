<template>
  <div class="px-5 md:px-0">
    <div
      class="relative border border-[#881D15] rounded-xl w-full md:w-2/3 lg:w-1/2 mx-auto py-3 md:py-5 px-2 md:-mt-20 z-20 bg-white"
    >
      <input
        type="text"
        placeholder="Search something..."
        class="w-full outline-none pl-3 pr-10"
      />
      <svg
        xmlns="http://www.w3.org/2000/svg"
        fill="none"
        viewBox="0 0 24 24"
        stroke-width="1.5"
        stroke="currentColor"
        class="size-6 absolute right-5 top-1/2 -translate-y-1/2"
      >
        <path
          stroke-linecap="round"
          stroke-linejoin="round"
          d="m21 21-5.197-5.197m0 0A7.5 7.5 0 1 0 5.196 5.196a7.5 7.5 0 0 0 10.607 10.607Z"
        />
      </svg>
    </div>
  </div>
  <div class="Container grid lg:grid-cols-3 gap-5 md:gap-10 mt-10">
    <div class="col-span-1">
      <div class="flex flex-col gap-5 md:w-2/3 lg:w-full">
        <div class="flex items-center gap-2 text-[#881D15]">
          <p class="uppercase lg:text-lg font-semibold">Notisia</p>
          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke-width="1.5"
            stroke="currentColor"
            class="size-6"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="m4.5 19.5 15-15m0 0H8.25m11.25 0v11.25"
            />
          </svg>
        </div>
        <p class="title-section text-[#1C1C1C]">Principais Notícias</p>
        <p class="text-lg">
          Ut Wisi Enim Ad Minim Veniam, Quis Nostrud Exerci Tation Ullamcorper
          Suscipit Lobortis Nisl Ut Aliquip Ex Ea Commodo Consequat.
        </p>
      </div>
    </div>
    <div class="hidden lg:block lg:col-span-2"></div>
    <div class="col-span-1">
      <div
        class="h-96 lg:h-[500px] w-full overflow-hidden rounded-4xl shadow bg-gradient-to-br from-[#881D15] to-black p-5 flex flex-col justify-between"
      >
        <div class="flex items-center justify-between">
          <p
            class="uppercase py-2 px-4 text-white bg-[#B82419] rounded-full text-sm md:text-base lg:text-xl"
          >
          Discurso
          </p>
          <div
            class="w-8 h-8 md:w-10 md:h-10 lg:w-14 lg:h-14 rounded-full flex items-center justify-center bg-[#881D15]"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="currentColor"
              class="size-6 text-[#FCF7AF]"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="m4.5 19.5 15-15m0 0H8.25m11.25 0v11.25"
              />
            </svg>
          </div>
        </div>
        <div class="flex flex-col gap-2 text-white">
          <p class="text-xs md:text-lg lg:text-xl">JAN 10, 2025</p>
          <p class="md:text-2xl lg:text-[28px]">
            Discurso de Abertura de Sua Excelência José Manuel Ramos-Horta Presidente da República Democrática de Timor-Leste Fórum AIS
          </p>
        </div>
      </div>
    </div>
    <div class="lg:col-span-2">
      <div
        class="relative w-full h-96 lg:h-full overflow-hidden rounded-4xl shadow"
      >
        <div
          class="relative w-full h-full p-5 flex flex-col justify-between z-30"
        >
          <div class="flex items-center justify-between">
            <p
              class="uppercase py-2 px-4 text-white bg-[#463F3F] rounded-full text-sm md:text-base lg:text-xl"
            >
              Notisia
            </p>
            <div
              class="w-8 h-8 md:w-10 md:h-10 lg:w-14 lg:h-14 rounded-full flex items-center justify-center bg-[#881D15]"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                class="size-6 text-[#FCF7AF]"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="m4.5 19.5 15-15m0 0H8.25m11.25 0v11.25"
                />
              </svg>
            </div>
          </div>
          <div class="flex flex-col gap-2 text-white">
            <p class="text-xs md:text-lg lg:text-xl">JAN 10, 2025</p>
            <p class="md:text-2xl lg:text-[28px]">
              I learned a lot about how to work in a team and face challenges in
              this bootcamp program. My study experience here has helped me
              broaden my professional network and prepared me for a career in
              technology.
            </p>
          </div>
        </div>
        <img
          src="../assets/news-1.svg"
          alt=""
          class="absolute top-0 left-0 w-full h-auto bg-black/30 z-10"
        />
        <div
          class="absolute top-0 left-0 w-full h-full bg-gradient-to-b from-black/30 to-black z-20"
        ></div>
      </div>
    </div>
    <div class="col-span-1">
      <div
        class="h-96 lg:h-[500px] w-full overflow-hidden rounded-4xl shadow bg-gradient-to-tl from-[#881D15] to-black p-5 flex flex-col justify-between"
      >
        <div class="flex items-center justify-between">
          <p
            class="uppercase py-2 px-4 text-white bg-[#B82419] rounded-full text-sm md:text-base lg:text-xl"
          >
          Discurso
          </p>
          <div
            class="w-8 h-8 md:w-10 md:h-10 lg:w-14 lg:h-14 rounded-full flex items-center justify-center bg-[#881D15]"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="currentColor"
              class="size-6 text-[#FCF7AF]"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="m4.5 19.5 15-15m0 0H8.25m11.25 0v11.25"
              />
            </svg>
          </div>
        </div>
        <div class="flex flex-col gap-2 text-white">
          <p class="text-xs md:text-lg lg:text-xl">JAN 25, 2025</p>
          <p class="md:text-2xl lg:text-[28px]">
            Discurso de Abertura de Sua Excelência José Manuel Ramos-Horta Presidente da República Democrática de Timor-Leste Fórum AIS
          </p>
        </div>
      </div>
    </div>
    <div class="lg:col-span-2">
      <div
        class="relative w-full h-96 lg:h-full overflow-hidden rounded-4xl shadow"
      >
        <div
          class="relative w-full h-full p-5 flex flex-col justify-between z-30"
        >
          <div class="flex items-center justify-between">
            <p
              class="uppercase py-2 px-4 text-white bg-[#463F3F] rounded-full text-sm md:text-base lg:text-xl"
            >
              Notisia
            </p>
            <div
              class="w-8 h-8 md:w-10 md:h-10 lg:w-14 lg:h-14 rounded-full flex items-center justify-center bg-[#881D15]"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                class="size-6 text-[#FCF7AF]"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="m4.5 19.5 15-15m0 0H8.25m11.25 0v11.25"
                />
              </svg>
            </div>
          </div>
          <div class="flex flex-col gap-2 text-white">
            <p class="text-xs md:text-lg lg:text-xl">JAN 10, 2025</p>
            <p class="md:text-2xl lg:text-[28px]">
              I learned a lot about how to work in a team and face challenges in
              this bootcamp program. My study experience here has helped me
              broaden my professional network and prepared me for a career in
              technology.
            </p>
          </div>
        </div>
        <img
          src="../assets/news-2.svg"
          alt=""
          class="absolute top-0 left-0 w-full h-auto bg-black/30 z-10"
        />
        <div
          class="absolute top-0 left-0 w-full h-full bg-gradient-to-b from-black/30 to-black z-20"
        ></div>
      </div>
    </div>
    <div class="col-span-1">
      <div
        class="h-96 lg:h-[500px] w-full overflow-hidden rounded-4xl shadow bg-gradient-to-br from-[#881D15] to-black p-5 flex flex-col justify-between"
      >
        <div class="flex items-center justify-between">
          <p
            class="uppercase py-2 px-4 text-white bg-[#B82419] rounded-full text-sm md:text-base lg:text-xl"
          >
          Discurso
          </p>
          <div
            class="w-8 h-8 md:w-10 md:h-10 lg:w-14 lg:h-14 rounded-full flex items-center justify-center bg-[#881D15]"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="currentColor"
              class="size-6 text-[#FCF7AF]"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="m4.5 19.5 15-15m0 0H8.25m11.25 0v11.25"
              />
            </svg>
          </div>
        </div>
        <div class="flex flex-col gap-2 text-white">
          <p class="text-xs md:text-lg lg:text-xl">FEV 10, 2025</p>
          <p class="md:text-2xl lg:text-[28px]">
            Discurso de Abertura de Sua Excelência José Manuel Ramos-Horta Presidente da República Democrática de Timor-Leste Fórum AIS
          </p>
        </div>
      </div>
    </div>
    <div class="lg:col-span-2">
      <div
        class="relative w-full h-96 lg:h-full overflow-hidden rounded-4xl shadow"
      >
        <div
          class="relative w-full h-full p-5 flex flex-col justify-between z-30"
        >
          <div class="flex items-center justify-between">
            <p
              class="uppercase py-2 px-4 text-white bg-[#463F3F] rounded-full text-sm md:text-base lg:text-xl"
            >
              Notisia
            </p>
            <div
              class="w-8 h-8 md:w-10 md:h-10 lg:w-14 lg:h-14 rounded-full flex items-center justify-center bg-[#881D15]"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                class="size-6 text-[#FCF7AF]"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="m4.5 19.5 15-15m0 0H8.25m11.25 0v11.25"
                />
              </svg>
            </div>
          </div>
          <div class="flex flex-col gap-2 text-white">
            <p class="text-xs md:text-lg lg:text-xl">JAN 10, 2025</p>
            <p class="md:text-2xl lg:text-[28px]">
              I learned a lot about how to work in a team and face challenges in
              this bootcamp program. My study experience here has helped me
              broaden my professional network and prepared me for a career in
              technology.
            </p>
          </div>
        </div>
        <img
          src="../assets/news-3.svg"
          alt=""
          class="absolute top-0 left-0 w-full h-auto bg-black/30 z-10"
        />
        <div
          class="absolute top-0 left-0 w-full h-full bg-gradient-to-b from-black/30 to-black z-20"
        ></div>
      </div>
    </div>
  </div>
</template>
