<template>
  <div class="q-pa-md">
    <q-carousel
      v-model="slide"
      transition-prev="slide-right"
      transition-next="slide-left"
      swipeable
      animated
      control-color="primary"
      navigation
      padding
      arrows
      height="300px"
      class="bg-white text-black shadow-1 rounded-borders no-shadow"
    >
      <q-carousel-slide :name="1" class="column no-wrap">
        <div class="row fit justify-start items-center q-gutter-xs q-col-gutter no-wrap">
            <!-- 引用图片 -->
          <q-img class="col-6 full-height" src="https://cdn.quasar.dev/img/mountains.jpg" />
          <q-img class="col-6 full-height" src="https://cdn.quasar.dev/img/parallax1.jpg" />
        </div>
      </q-carousel-slide>
      <q-carousel-slide :name="2" class="column no-wrap">
        <div class="row fit justify-start items-center q-gutter-xs q-col-gutter no-wrap">
          <q-img class="col-6 full-height" src="https://cdn.quasar.dev/img/parallax2.jpg" />
          <q-img class="col-6 full-height" src="https://cdn.quasar.dev/img/quasar.jpg" />
        </div>
      </q-carousel-slide>
      <q-carousel-slide :name="3" class="column no-wrap">
        <div class="row fit justify-start items-center q-gutter-xs q-col-gutter no-wrap">
          <q-img class="col-6 full-height" src="https://cdn.quasar.dev/img/cat.jpg" />
          <q-img class="col-6 full-height" src="https://cdn.quasar.dev/img/linux-avatar.png" />
        </div>
      </q-carousel-slide>
      <q-carousel-slide :name="4" class="column no-wrap">
        <div class="row fit justify-start items-center q-gutter-xs q-col-gutter no-wrap">
          <q-img class="col-6 full-height" src="https://cdn.quasar.dev/img/material.png" />
          <q-img class="col-6 full-height" src="https://cdn.quasar.dev/img/donuts.png" />
        </div>
      </q-carousel-slide>
    </q-carousel>
  </div>
</template>

<script>
// import carousel from 'src/components/carousel'
export default {
    // components:{
        // "carousel":carousel
    // },
  data () {
    return {
      slide: 1
    }
  }
}
</script>