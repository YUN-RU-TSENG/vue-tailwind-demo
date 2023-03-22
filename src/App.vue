<script setup></script>

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
      <a class="cursor-pointer text-[18px]">#LIVE NEW CJ</a>
      <a class="cursor-pointer text-[18px]">CJ Now</a>
      <a class="cursor-pointer text-[18px]">Brand</a>
      <a class="cursor-pointer text-[18px]">Sustainability</a>
      <div class="text-[18px]">
        <div class="h-[22px] w-[1px] bg-[#d8d8d8]"></div>
      </div>
      <a class="cursor-pointer text-[18px]">CJ소개</a>
      <a class="cursor-pointer text-[18px]">인재채용</a>
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
      <a
        href=""
        class="inline-block rounded-tr-[25%] rounded-bl-[25%] border px-[10px] py-[10px] text-[14px]"
        v-for="key in 10"
        :key="key"
        >#전체</a
      >
    </section>
    <section class="mb-[48px] flex flex-wrap justify-between gap-y-[48px]">
      <section class="basis-[330px]" v-for="key in 10" :key="key">
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
            꼰대미 1도 없는 사기캐(?)🧙🏻‍♂️ 올리브영 최연소 사업부장님 브이로그에 온
            걸 환영해.
          </p>
          <div>
            <a
              href=""
              class="mr-[12px] inline-block rounded-tr-[25%] rounded-bl-[25%] border px-[10px] py-[10px] text-[14px]"
              >#전체</a
            >
            <a
              href=""
              class="mr-[12px] inline-block rounded-tr-[25%] rounded-bl-[25%] border px-[10px] py-[10px] text-[14px]"
              >#전체</a
            >
            <a
              href=""
              class="inline-block rounded-tr-[25%] rounded-bl-[25%] border px-[10px] py-[10px] text-[14px]"
              >#전체</a
            >
          </div>
        </section>
      </section>
    </section>
  </main>
  <footer class="border-t py-[48px]">
    <div class="m-auto w-[1100px]">
      <ul class="mb-[48px] flex flex-wrap justify-between">
        <div v-for="key in 6" :key="key">
          <h3 class="mb-[6px] text-[18px] font-[400]">#LIVE NEW CJ</h3>
          <ul>
            <li class="mb-[4px] cursor-pointer text-[16px] hover:underline">
              Best Brand
            </li>
            <li class="mb-[4px] cursor-pointer text-[16px] hover:underline">
              건강
            </li>
            <li class="mb-[4px] cursor-pointer text-[16px] hover:underline">
              즐거움
            </li>
            <li class="mb-[4px] cursor-pointer text-[16px] hover:underline">
              편리
            </li>
          </ul>
        </div>
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
        <a href="" class="font-[12px] hover:underline"
          ><img
            class="h-[24px] w-[24px]"
            src="https://images.cj.net/images/footer/footer_sns_facebook@2x.png"
            alt=""
        /></a>
        <a href="" class="font-[12px] hover:underline"
          ><img
            class="h-[24px] w-[24px]"
            src="https://images.cj.net/images/footer/footer_sns_facebook@2x.png"
            alt=""
        /></a>
        <a href="" class="font-[12px] hover:underline"
          ><img
            class="h-[24px] w-[24px]"
            src="https://images.cj.net/images/footer/footer_sns_facebook@2x.png"
            alt=""
        /></a>
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

<style scoped></style>
