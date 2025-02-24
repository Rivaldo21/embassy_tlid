<script setup lang="ts">
import Accordion from "./Accordion.vue";
</script>

<template>
  <div class="Container">
    <div class="grid md:grid-cols-2 gap-10">
      <div class="flex flex-col gap-5">
        <p class="text-lg font-semibold">FAQS</p>
        <p class="title-section">Frequently Asked Questions</p>
        <hr />
        <p>
          Ut Wisi Enim Ad Minim Veniam, Quis Nostrud Exerci Tation Ullamcorper
          Suscipit Lobortis Nisl Ut Aliquip Ex Ea Commodo Consequat.
        </p>
      </div>
      <div>
        <Accordion
          title="Lorem Ipsum Dolor Sit Amet Consectetuer?  "
          answer="Lorem Ipsum Dolor Sit Amet Consectetuer?  "
        />
        <Accordion
          title="Lorem Ipsum Dolor Sit Amet Consectetuer?  "
          answer="Lorem Ipsum Dolor Sit Amet Consectetuer?  "
        />
        <Accordion
          title="Lorem Ipsum Dolor Sit Amet Consectetuer?  "
          answer="Lorem Ipsum Dolor Sit Amet Consectetuer?  "
        />
        <Accordion
          title="Lorem Ipsum Dolor Sit Amet Consectetuer?  "
          answer="Lorem Ipsum Dolor Sit Amet Consectetuer?  "
        />
        <Accordion
          title="Lorem Ipsum Dolor Sit Amet Consectetuer?  "
          answer="Lorem Ipsum Dolor Sit Amet Consectetuer?  "
        />
      </div>
    </div>
  </div>
</template>
