<script setup>
import NavbarItem from "./NavbarItem.vue";
</script>

<template>
  <nav class="mb-[48px] border-b py-[20px]">
    <div class="mx-auto flex w-[1100px] items-center justify-between">
      <a class="mr-[20px] text-[18px]">
        <img
          class="inline-block h-[50px] w-[58px]"
          src="https://images.cj.net/images/common/cj_logo.png"
          alt="logo cj"
        />
      </a>
      <NavbarItem>#LIVE NEW CJ</NavbarItem>
      <NavbarItem>CJ Now</NavbarItem>
      <NavbarItem>Brand</NavbarItem>
      <NavbarItem>Sustainability</NavbarItem>
      <div class="text-[18px]">
        <div class="h-[22px] w-[1px] bg-[#d8d8d8]"></div>
      </div>
      <NavbarItem>CJ소개</NavbarItem>
      <NavbarItem>인재채용</NavbarItem>
      <div class="ml-[56px] flex items-center">
        <a href="" class="mr-[24px] cursor-pointer text-[16px]">KOR</a>
        <a class="cursor-pointer text-[36px]"
          ><img
            width="32px"
            height="32px"
            src="https://images.cj.net/images/common/icon_gnb_search2@2x.png"
            alt=""
        /></a>
      </div>
    </div>
  </nav>
</template>

<style scoped></style>
