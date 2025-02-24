<script setup>
import { Menu, MenuButton, MenuItems, MenuItem } from "@headlessui/vue";
import { ChevronDownIcon } from "@heroicons/vue/20/solid";

const itemHeader = [
  "Home",
  "Perfil",
  "Serviços Consulares",
  "Relações Diplomáticas",
  "Consultores e Oportunidades",
  "Galeria",
  "Contactos",
];
</script>

<template>
  <div class="container-x flex items-center justify-between py-5">
    <div class="flex items-center gap-1">
      <img
        src="../assets/logo.svg"
        alt=""
        class="h-10 md:h-16 lg:h-[68px] w-auto"
      />
      <div class="capitalize text-xl lg:text-4xl">
        <p>Embaixada TL</p>
        <p class="-mt-2">Indonesia</p>
      </div>
    </div>
    <div class="flex items-center gap-5 2xl:gap-10 text-sm font-semibold">
      <p
        v-for="(item, index) in itemHeader"
        :key="index"
        :class="{
          'border-b-2 text-[#881D15] border-[#881D15]': item === 'Home',
        }"
        class="cursor-pointer hover:border-b-2 hover:border-[#881D15] hover:text-[#881D15] hidden lg:block"
      >
        {{ item }}
      </p>
    </div>
    <div class="flex items-center divide-x-2">
      <p class="font-medium text-sm pr-5">TL</p>
      <div class="pl-5 flex items-center gap-2">
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
            d="M15 10.5a3 3 0 1 1-6 0 3 3 0 0 1 6 0Z"
          />
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M19.5 10.5c0 7.142-7.5 11.25-7.5 11.25S4.5 17.642 4.5 10.5a7.5 7.5 0 1 1 15 0Z"
          />
        </svg>

        <Menu as="div" class="relative inline-block text-left">
          <div>
            <MenuButton
              class="inline-flex w-full justify-center rounded-md text-sm font-medium text-black cursor-pointer"
            >
              Jakarta
              <ChevronDownIcon
                class="-mr-1 ml-2 h-5 w-5 text-black"
                aria-hidden="true"
              />
            </MenuButton>
          </div>

          <transition
            enter-active-class="transition duration-100 ease-out"
            enter-from-class="transform scale-95 opacity-0"
            enter-to-class="transform scale-100 opacity-100"
            leave-active-class="transition duration-75 ease-in"
            leave-from-class="transform scale-100 opacity-100"
            leave-to-class="transform scale-95 opacity-0"
          >
            <MenuItems
              class="absolute right-0 mt-2 w-auto origin-top-right divide-y divide-gray-100 rounded-md bg-white shadow-lg ring-1 ring-black/5 focus:outline-none"
            >
              <div class="px-1 py-1">
                <MenuItem v-slot="{ active }">
                  <button
                    :class="[
                      active ? 'bg-black text-white' : 'text-gray-900',
                      'group flex w-full items-center rounded-md px-2 py-2 text-sm',
                    ]"
                  >
                    Denpasar
                  </button>
                </MenuItem>
              </div>
              <MenuItem v-slot="{ active }">
                  <button
                    :class="[
                      active ? 'bg-black text-white' : 'text-gray-900',
                      'group flex w-full items-center rounded-md px-2 py-2 text-sm',
                    ]"
                  >
                    Kupang
                  </button>
                </MenuItem>
                <div class="px-1 py-1">
                <MenuItem v-slot="{ active }">
                  <button
                    :class="[
                      active ? 'bg-black text-white' : 'text-gray-900',
                      'group flex w-full items-center rounded-md px-2 py-2 text-sm',
                    ]"
                  >
                    Atambua
                  </button>
                </MenuItem>
              </div>
            </MenuItems>
          </transition>
        </Menu>
      </div>
    </div>
  </div>
</template>
