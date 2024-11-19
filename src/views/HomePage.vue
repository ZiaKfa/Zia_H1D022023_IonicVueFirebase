<template>
  <ion-page>
    <ion-header :translucent="true">
      <ion-toolbar>
        <ion-title>Home</ion-title>
      </ion-toolbar>
    </ion-header>

    <ion-content :fullscreen="true">
      <div>
        <ion-card>
          <ion-card-header>
            <ion-card-title>Selamat Datang !</ion-card-title>
          </ion-card-header>
          <ion-card-content>
           Ini adalah halaman home
          </ion-card-content>
        </ion-card>
      </div>
      <TabsMenu />
    </ion-content>

  </ion-page>
</template>

<script setup lang="ts">
import { IonContent, IonHeader, IonPage, IonTitle, IonToolbar } from '@ionic/vue';
import TabsMenu from '@/components/TabsMenu.vue';
</script>
