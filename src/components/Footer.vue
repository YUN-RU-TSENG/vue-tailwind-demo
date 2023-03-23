<script setup>
import List from "./List.vue";
import ListItem from "./ListItem.vue";
</script>

<template>
  <footer class="border-t py-[48px]">
    <div class="m-auto w-[1100px]">
      <ul class="mb-[48px] flex flex-wrap justify-between">
        <List v-for="key in 6" :key="key">
          <ListItem> Best Brand</ListItem>
          <ListItem> 건강</ListItem>
          <ListItem> 즐거움</ListItem>
          <ListItem> 편리</ListItem>
        </List>
      </ul>
      <section
        class="mb-[12px] flex flex-wrap content-center justify-between gap-x-[12px]"
      >
        <a href="" class="origin-left scale-75 font-[12px] hover:underline"
          >개인정보처리방침</a
        >
        <a href="" class="origin-left scale-75 font-[12px] hover:underline"
          >이용약관</a
        >
        <a href="" class="origin-left scale-75 font-[12px] hover:underline"
          >공지사항</a
        >
        <a href="" class="origin-left scale-75 font-[12px] hover:underline"
          >고객센터</a
        >
        <a
          href=""
          class="ml-auto p-[6px] font-[12px] transition-all hover:bg-slate-400"
          >계열사 바로가기</a
        >
      </section>
      <section
        class="mb-[12px] flex flex-wrap content-center justify-between gap-x-[12px]"
      >
        <a href="" class="origin-left scale-50 font-[12px] hover:underline"
          >개인정보처리방침</a
        >
        <a href="" class="ml-auto font-[12px] hover:underline"
          ><img
            class="h-[24px] w-[24px]"
            src="https://images.cj.net/images/footer/img_wa@2x.png"
            alt=""
        /></a>
        <a href="" class="font-[12px] hover:underline">
          <img
            class="h-[24px] w-[24px]"
            src="https://images.cj.net/images/footer/footer_sns_facebook@2x.png"
            alt=""
          />
        </a>
        <a href="" class="font-[12px] hover:underline">
          <img
            class="h-[24px] w-[24px]"
            src="https://images.cj.net/images/footer/footer_sns_facebook@2x.png"
            alt=""
          />
        </a>
        <a href="" class="font-[12px] hover:underline">
          <img
            class="h-[24px] w-[24px]"
            src="https://images.cj.net/images/footer/footer_sns_facebook@2x.png"
            alt=""
          />
        </a>
        <a href="" class="font-[12px] hover:underline"
          ><img
            class="h-[24px] w-[24px]"
            src="https://images.cj.net/images/footer/footer_sns_facebook@2x.png"
            alt=""
        /></a>
      </section>
    </div>
  </footer>
</template>

<style></style>
