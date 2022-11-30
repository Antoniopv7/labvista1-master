<template>
  <ion-page>
    <ion-header>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Profile</ion-title>
        </ion-toolbar>
      </ion-header>
      
      <ion-row><ion-col size="12"></ion-col></ion-row>
      <ion-row><ion-col size="12"></ion-col></ion-row>
      <ion-row><ion-col size="12"></ion-col></ion-row>
      <ion-row><ion-col size="12"></ion-col></ion-row>
      <ion-row><ion-col size="12"></ion-col></ion-row>
      <ion-row>
        <ion-col size="5"></ion-col>
        <ion-col size="3">
          <ion-title>Perfil</ion-title>
        </ion-col>
        <ion-col size="4"></ion-col>
      </ion-row>
      <ion-row><ion-col size="12"></ion-col></ion-row>
      <ion-row><ion-col size="12"></ion-col></ion-row>
      <ion-row><ion-col size="12"></ion-col></ion-row>
      <ion-row><ion-col size="12"></ion-col></ion-row>

      <ion-list>
        <ion-item>
          <ion-label>Nombres : </ion-label>
          <ion-input></ion-input>
        </ion-item>
        <ion-item>
          <ion-label>Apellidos : </ion-label>
          <ion-input></ion-input>
        </ion-item>
        <ion-item>
          <ion-label>Edad : </ion-label>
          <ion-input></ion-input>
        </ion-item>
        <ion-item>
          <ion-label>Rut : </ion-label>
          <ion-input></ion-input>
        </ion-item>
        <ion-item>
          <ion-label>Direccion : </ion-label>
          <ion-input></ion-input>
        </ion-item>
        <ion-item>
          <ion-label>Numero Telefonico : </ion-label>
          <ion-input></ion-input>
        </ion-item>
        <ion-item>
          <ion-label>Sexo : </ion-label>
          <ion-input></ion-input>
        </ion-item>
        <ion-item>
          <ion-label>Nacionalidad : </ion-label>
          <ion-input></ion-input>
        </ion-item>
      </ion-list>

      
      <ion-row>
        <ion-col size="12"></ion-col>
      </ion-row>
      <ion-row>        
        <ion-col size="12"></ion-col>        
      </ion-row>
      <ion-row>
        <ion-col size="12"></ion-col>
      </ion-row>
      <ion-row>
        <ion-col size="12"></ion-col>
      </ion-row>
      <ion-row>
        <ion-col size="2"></ion-col>
        <ion-col size="8">
          <ion-button color="medium" expand="block">Actualizar</ion-button>
        </ion-col>
        <ion-col size="2"></ion-col>
      </ion-row>
      <ion-row>
        <ion-col size="2"></ion-col>
        <ion-col size="8">
          <ion-button color="medium" expand="block">Eliminar</ion-button>
        </ion-col>
        <ion-col size="2"></ion-col>
      </ion-row>
      
      
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent, IonInput, IonList, IonLabel, IonItem, IonCol, IonRow, IonButton } from '@ionic/vue';

export default defineComponent({
  name: 'Tab2Page',
  components: { IonHeader, IonToolbar, IonTitle, IonContent, IonPage, IonInput, IonList, IonLabel, IonItem, IonCol, IonRow, IonButton }
});
</script>
