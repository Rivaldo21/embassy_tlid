<template>
  <div class="py-3 md:py-5">
    <button
      @click="toggleAccordion"
      class="flex justify-between w-full mb-2 pb-2 border-b-2 border-[#707070] text-start"
    >
      <span class="text-lg lg:text-2xl">{{ title }}</span>
      <svg
        class="fill-[#881D15] shrink-0 ml-8"
        width="16"
        height="16"
        xmlns="http://www.w3.org/2000/svg"
      >
        <rect
          y="7"
          width="16"
          height="2"
          rx="1"
          :class="{
            'transform origin-center transition duration-200 ease-out': true,
            '!rotate-180': accordionOpen,
          }"
        />
        <rect
          y="7"
          width="16"
          height="2"
          rx="1"
          :class="{
            'transform origin-center rotate-90 transition duration-200 ease-out': true,
            '!rotate-180': accordionOpen,
          }"
        />
      </svg>
    </button>
    <div
      :class="[
        'grid overflow-hidden transition-all duration-300 ease-in-out text-sm',
        accordionOpen
          ? 'grid-rows-[1fr] opacity-100'
          : 'grid-rows-[0fr] opacity-0',
      ]"
    >
      <div class="overflow-hidden text-sm lg:text-base">{{ answer }}</div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    title: String,
    answer: String,
  },
  data() {
    return {
      accordionOpen: false,
    };
  },
  methods: {
    toggleAccordion() {
      this.accordionOpen = !this.accordionOpen;
    },
  },
};
</script>
