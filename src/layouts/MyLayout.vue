<template>
  <q-layout view="lHh Lpr lFf">
    <q-header class="bg-white text-blue">
      <q-toolbar>
        <q-avatar>
          <img src="https://upload.wikimedia.org/wikipedia/commons/1/18/Nano_logo.png">
        </q-avatar>
        <q-toolbar-title>
          Nano <span class="text-red">Tube</span>
        </q-toolbar-title>

        <div>Login</div>
      </q-toolbar>
    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script>
import { openURL } from 'quasar'

export default {
  name: 'MyLayout',
  data () {
    return {
      leftDrawerOpen: this.$q.platform.is.desktop
    }
  },
  methods: {
    openURL
  }
}
</script>

<style>
</style>
