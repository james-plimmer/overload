<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Track</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Tab 2</ion-title>
        </ion-toolbar>
      </ion-header>

      <ion-fab vertical="center" horizontal="center">
        <ion-button @click="router.push('/session')">
          <h1>New Session</h1>
        </ion-button>
      </ion-fab>

    </ion-content>
  </ion-page>
</template>

<script setup lang="ts">
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent, IonFab, IonFabButton } from '@ionic/vue';
import {  } from 'ionicons/icons';
import { useRouter } from 'vue-router';
const router = useRouter();
</script>

<style scoped>
</style>  
