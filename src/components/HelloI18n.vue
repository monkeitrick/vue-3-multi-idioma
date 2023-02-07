<template>
  <h1>{{ $t("title") }}</h1>
  <p>{{ $t("description") }}</p>
  <LocaleSwitcher/>
</template>

<script>
// import { defineComponent } from 'vue'
// import { useI18n } from 'vue-i18n'
import LocaleSwitcher from './LocaleSwitcher.vue'; 
export default{
  name: 'HelloI18n',
  components: {LocaleSwitcherVue}
  // setup
  //   const  t  = useI18n
  //     inheritLocale: true,
  //     useScope: 'local'
  //   

  //   // Something todo ..

  //   return  t 
  // 
};
</script>

<i18n>
{
  "en": {
    "hello": "Hello i18n in SFC!"
  }
}
</i18n>
