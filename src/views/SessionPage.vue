<template>
    <ion-page>
      <ion-header>
        <ion-toolbar>
          <ion-buttons slot="start">
            <ion-back-button default-href="/tabs/tab1"></ion-back-button>
          </ion-buttons>
          <ion-title>Session</ion-title>
        </ion-toolbar>
      </ion-header>
      <ion-content></ion-content>
    </ion-page>
  </template>
  
  <script setup lang="ts">
    import { IonBackButton, IonButtons, IonContent, IonHeader, IonPage, IonTitle, IonToolbar } from '@ionic/vue';
  </script>