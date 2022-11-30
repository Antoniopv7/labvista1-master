<template>  
  <ion-page>
    <ion-header>
      
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Home</ion-title>
        </ion-toolbar>
      </ion-header>

      <ion-row><ion-col size="12"></ion-col></ion-row>
      <ion-row><ion-col size="12"></ion-col></ion-row>
      <ion-row><ion-col size="12"></ion-col></ion-row>
      <ion-row><ion-col size="12"></ion-col></ion-row>
      <ion-row><ion-col size="12"></ion-col></ion-row>
      <ion-row><ion-col size="12"></ion-col></ion-row>
      <ion-row><ion-col size="12"></ion-col></ion-row>
      <ion-row><ion-col size="12"></ion-col></ion-row>
      <ion-row><ion-col size="12"></ion-col></ion-row>
      <ion-row><ion-col size="12"></ion-col></ion-row>
      <ion-row><ion-col size="12"></ion-col></ion-row>      
      <ion-row>
        <ion-col size="3"></ion-col>
        <ion-col size="8">
          <ion-title>Reconocimiento Facial</ion-title>
        </ion-col>
        <ion-col size="1"></ion-col>
      </ion-row>
      <ion-row>
        <ion-col size="4"></ion-col>
        <ion-col size="5">
          <ion-label>Para controlar asistencia</ion-label>
        </ion-col>
        <ion-col size="3"></ion-col>
      </ion-row>
      <ion-row><ion-col size="12"></ion-col></ion-row>
      <ion-row><ion-col size="12"></ion-col></ion-row>
      <ion-row><ion-col size="12"></ion-col></ion-row>
      <ion-row><ion-col size="12"></ion-col></ion-row>
      <ion-row><ion-col size="12"></ion-col></ion-row>
      <ion-row><ion-col size="12"></ion-col></ion-row>
      <ion-row><ion-col size="12"></ion-col></ion-row>
      <ion-row><ion-col size="12"></ion-col></ion-row>
      <ion-row><ion-col size="12"></ion-col></ion-row>
      <ion-row><ion-col size="12"></ion-col></ion-row>
      <ion-row><ion-col size="12"></ion-col></ion-row>
      <ion-row><ion-col size="12"></ion-col></ion-row>
      <ion-row><ion-col size="12"></ion-col></ion-row>
      <ion-row><ion-col size="12"></ion-col></ion-row>
      <ion-row size="12">
        <ion-col size="2.4"></ion-col>
        <ion-col size="1.6">
          <ion-button color="secondary">
            <ion-icon slot="icon-only" :icon="cameraOutline"></ion-icon>
          </ion-button>
        </ion-col>
        <ion-col size="6">
          <ion-button color="secondary" expand="block">Tomar Foto Rostro</ion-button>
        </ion-col>
        <ion-col size="2"></ion-col>
      </ion-row>
      <ion-row size="12">
        <ion-col size="2.4"></ion-col>
        <ion-col size="1.6">
          <ion-button color="danger">
            <ion-icon slot="icon-only" :icon="barbellOutline"></ion-icon>
          </ion-button>
        </ion-col>
        <ion-col size="6">
          <ion-button color="danger" expand="block">Entrenar Modelo IA</ion-button>
        </ion-col>
        <ion-col size="2"></ion-col>
      </ion-row>
      <ion-row size="12">
        <ion-col size="2.4"></ion-col>
        <ion-col size="1.6">
          <ion-button color="medium">
            <ion-icon slot="icon-only" :icon="caretDownCircleOutline"></ion-icon>
          </ion-button>
        </ion-col>
        <ion-col size="6">
          <ion-button color="medium" expand="block">Reconocer Rostro</ion-button>
        </ion-col>
        <ion-col size="2"></ion-col>
      </ion-row>

    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent, IonButton, IonCol, IonRow, IonIcon, IonLabel } from '@ionic/vue';
import { star, cameraOutline, barbellOutline, caretDownCircleOutline } from 'ionicons/icons';

export default  defineComponent({
  name: 'Tab1Page',
  components: { IonHeader, IonToolbar, IonTitle, IonContent, IonPage, IonButton, IonCol, IonRow, IonIcon, IonLabel },
  setup(){
    return {
      star,
      cameraOutline,
      barbellOutline,
      caretDownCircleOutline,
    }
  }
});
</script>

<style scoped>

</style>
