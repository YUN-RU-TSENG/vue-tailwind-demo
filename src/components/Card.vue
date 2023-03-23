<script setup>
import Tag from "./Tag.vue";
</script>

<template>
  <section class="basis-[330px]">
    <header
      class="mb-[24px] h-[180px] w-[340px] cursor-pointer overflow-hidden"
    >
      <img
        class="transition-all hover:scale-125"
        src="https://images.cj.net/upfiles/bbs/0000007323264006062959673.png"
        alt=""
      />
    </header>
    <section class="">
      <p class="mb-[24px] cursor-pointer text-[18px]">
        꼰대미 1도 없는 사기캐(?)🧙🏻‍♂️ 올리브영 최연소 사업부장님 브이로그에 온 걸
        환영해.
      </p>
      <div>
        <Tag v-for="key in 3" :key="key">#전체</Tag>
      </div>
    </section>
  </section>
</template>

<style></style>
