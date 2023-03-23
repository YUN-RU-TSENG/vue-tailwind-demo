<script setup>
import Navbar from "./components/Navbar.vue";
import Card from "./components/Card.vue";
import Tag from "./components/Tag.vue";
import Footer from "./components/Footer.vue";
</script>

<template>
  <Navbar></Navbar>
  <main class="mx-auto w-[1100px]">
    <section class="py-[84px] text-center">
      <img
        class="mb-[20px] inline-block h-[66px] w-[260px]"
        src="https://images.cj.net/images/cjNow/title_cjnow@2x.png"
        alt=""
      />
      <p class="text-[26px]">CJ의 최신 소식을 지금 만나보세요</p>
    </section>
    <section class="mb-[80px] flex gap-[12px] px-[24px]">
      <Tag v-for="key in 10" :key="key">#전체</Tag>
    </section>
    <section class="mb-[48px] flex flex-wrap justify-between gap-y-[48px]">
      <Card class="basis-[330px]" v-for="key in 10" :key="key"></Card>
    </section>
  </main>
  <Footer></Footer>
</template>

<style scoped></style>
