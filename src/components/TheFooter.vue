<script setup>
  import { RouterLink } from 'vue-router';

</script>

<template>
    <v-footer class="d-flex flex-column">
        <div align="center" class="px-4 py-2 bg-black text-center w-100">
            {{ new Date().getFullYear() }} <strong>- Vuetify</strong>
        </div>
    </v-footer>
    </template>

<style scoped>
    #navegador ul {
        list-style-type: none;
        text-align: center;
    }

    #navegador li {
        display: inline;
        text-align: center;
        margin: 0 10px 0 0;
    }

        #navegador li a {
            padding: 2px 7px 2px 7px;
            color: #666;
            background-color: #eeeeee;
            border: 1px solid #ccc;
            text-decoration: none;
        }

            #navegador li a:hover {
                background-color: #333333;
                color: #ffffff;
            }
</style>