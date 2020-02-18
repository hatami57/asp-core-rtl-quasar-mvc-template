<template>
    <q-layout view="hHh lpR fFf">

        <q-header elevated class="bg-primary text-white">
            <q-toolbar>
                <q-toolbar-title>
                    Quasar Project
                </q-toolbar-title>
            </q-toolbar>
        </q-header>

        <q-page-container>
            <q-page padding>
                <slot></slot>
            </q-page>
        </q-page-container>

    </q-layout>
</template>

<script>
  
  export default {
    data: function () {
      return {
      }
    },
    methods: {
    }
  }
</script>