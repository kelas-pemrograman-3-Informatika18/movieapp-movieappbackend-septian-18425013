<template>
  <q-page padding class="bg-indigo-10 glossy">
    <div class="q-pa-md row items-start q-gutter-md">
    <q-card
      class="my-card text-white"
      style="background: transparent"
      flat
    >
      <q-card-section>
        <div class="text-h6">Tentang Aplikasi</div>
        <div class="text-subtitle2">Movie APP</div>
      </q-card-section>

      <q-card-section class="q-pt-none">
        {{ tentang }}
      </q-card-section>
      <div class="q-pa-md row items-start q-gutter-md">
      </div>
    </q-card>
    </div>
  </q-page>
</template>
<script>
export default {
  data () {
    return {
      tentang: 'MovieApp merupakan aplikasi yang digunakan untuk memesan film dengan kualitas HD dan dikirimkan dengan bentuk CD dan diantar ke customer melalui kurir/GO-Send'
    }
  }
}
</script>
