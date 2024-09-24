<!-- <script setup></script> -->

<template>
  <header>
    <q-tabs>
      <q-route-tab to="/" label="Home"></q-route-tab>
      <q-route-tab to="/welcome" label="Welcome Page"></q-route-tab>
      <q-route-tab to="/goodbye" label="goodbye Page"></q-route-tab>
      <q-route-tab to="/logout" label="Abmeldescreen"></q-route-tab>
      <q-route-tab to="/inputBasicData" label="Eingabefelder"></q-route-tab>
    </q-tabs>
  </header>

  <RouterView />
</template>

<style>
@font-face {
  font-family: 'Montserrat';
  src: url('/fonts/Montserrat/Montserrat-Regular.ttf') format('truetype');
}

* {
  font-family: 'Montserrat';
}

@tailwind base;
@tailwind components;
@tailwind utilities;
</style>
