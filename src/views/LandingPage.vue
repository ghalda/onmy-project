<template>
    <div id="LandingPage">
      <header-comp/>
      <HeroBanner/>
      <TitleList/>
      <ClassRec/>
      <WhyComp/>
      <ArticleBanner/>
      <PartnerComp/>
      <NewsletterComp/>
      <footer-comp/>
    </div>
  </template>
  
  <script>
  import HeaderComp from '@/components/HeaderComp.vue'
  import FooterComp from '@/components/FooterComp.vue'
  import NewsletterComp from '@/components/NewsletterComp.vue';
  import HeroBanner from '@/components/HeroBanner.vue';
  import ClassRec from '@/components/ClassRec.vue';
  import WhyComp from '@/components/WhyComp.vue';
  import ArticleBanner from '@/components/ArticleBanner.vue';
  import TitleList from '@/components/TitleList.vue';
  import PartnerComp from '@/components/PartnerComp.vue';
  
  export default {
      name: 'LandingPage',
      components: {
    HeaderComp,
    FooterComp,
    NewsletterComp,
    HeroBanner,
    ClassRec,
    WhyComp,
    ArticleBanner,
    TitleList,
    PartnerComp
}
  }
  </script>
  
  <style>
  
  </style>