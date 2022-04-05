<template>
  <q-layout view="lHh Lpr lFf">
    <q-header class="navi">
      <q-toolbar>

        <q-toolbar-title>
         Inicio
        </q-toolbar-title>
        <q-toolbar-title>
         Secretaria
        </q-toolbar-title>
        <q-toolbar-title>
         Programa
        </q-toolbar-title>
        <q-toolbar-title>
         Pesquisa
        </q-toolbar-title>
        <q-toolbar-title>
         Informações aos alunos
        </q-toolbar-title>
        <q-toolbar-title>
         Processo seletivo
        </q-toolbar-title>
         <q-toolbar-title>
         Teses e Dissertações
        </q-toolbar-title>
         <q-toolbar-title>
         Seminário Geral
        </q-toolbar-title>

      </q-toolbar>
    </q-header>


    <q-page-container class="main-container">
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<style>
.main-container {
margin-top: 0 !important;
    width: 85%;
    margin: 0 auto;
}
.navi {
background-color: #bf0000;
    width: 85%;
    margin: 0 auto;
}
</style>

<script>
import { defineComponent, ref } from 'vue'
export default defineComponent({
  name: 'MainLayout',
  setup () {
    return {}
  }
})
</script>
