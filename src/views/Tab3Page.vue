<template>
  <ion-page>
    <ion-header>

    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Subjects</ion-title>
        </ion-toolbar>
      </ion-header>
      
      <ion-row><ion-col size="12"></ion-col></ion-row>
      <ion-row><ion-col size="12"></ion-col></ion-row>
      <ion-row><ion-col size="12"></ion-col></ion-row>
      <ion-row><ion-col size="12"></ion-col></ion-row>
      <ion-row><ion-col size="12"></ion-col></ion-row>
      <ion-row>
        <ion-col size="2"></ion-col>
        <ion-col size="9">
          <ion-title>Control de horarios y Asistencia</ion-title>
        </ion-col>
        <ion-col size="1"></ion-col>
      </ion-row>
      <ion-row><ion-col size="12"></ion-col></ion-row>
      <ion-row><ion-col size="12"></ion-col></ion-row>
      <ion-row><ion-col size="12"></ion-col></ion-row>
      <ion-row><ion-col size="12"></ion-col></ion-row>
      <ion-list>
        <ion-item>
          <ion-select placeholder="Seleccione Ramo" :multiple="true">
          <ion-select-option value="base de datos">Base de datos</ion-select-option>
          <ion-select-option value="programacion de aplicaciones">Programacion de aplicaciones</ion-select-option>
          <ion-select-option value="taller integrador 2">Taller integrador 2</ion-select-option>
        </ion-select>
        </ion-item>
      </ion-list>
      <ion-list>
        <ion-item>
          <ion-select placeholder="Seleccione Profesor" :multiple="true">
          <ion-select-option value="Alejandro Sanhueza">Alejandro Sanhueza</ion-select-option>
          <ion-select-option value="Juan Perez">Juan Perez</ion-select-option>
          <ion-select-option value="Camila Rosas">Camila Rosas</ion-select-option>
        </ion-select>
        </ion-item>
      </ion-list>
      <ion-list>
        <ion-item>
          <ion-select placeholder="Seleccione Seccion" :multiple="true">
          <ion-select-option value="10">10</ion-select-option>
          <ion-select-option value="11">11</ion-select-option>
          <ion-select-option value="12">12</ion-select-option>
        </ion-select>
        </ion-item>
      </ion-list>
      <ion-list>
        <ion-item>
          <ion-select placeholder="Seleccione Turno" :multiple="true">
          <ion-select-option value="Diurno">Diurno</ion-select-option>
          <ion-select-option value="Vespertino">Vespertino</ion-select-option>
        </ion-select>
        </ion-item>
      </ion-list>
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
        <ion-col size="2"></ion-col>
        <ion-col size="8">
          <ion-button color="medium" expand="block">Consultar Horario</ion-button>
        </ion-col>
        <ion-col size="2"></ion-col>
      </ion-row>
      <ion-row>
        <ion-col size="2"></ion-col>
        <ion-col size="8">
          <ion-button color="medium" expand="block">Consultar nivel de asistencia</ion-button>
        </ion-col>
        <ion-col size="2"></ion-col>
      </ion-row>
      <ion-row>
        <ion-col size="2"></ion-col>
        <ion-col size="8">
          <ion-button color="medium" expand="block">Reiniciar</ion-button>
        </ion-col>
        <ion-col size="2"></ion-col>
      </ion-row>
      
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent, IonSelect, IonItem, IonSelectOption, IonList, IonRow, IonCol, IonButton, } from '@ionic/vue';

export default defineComponent({
  name: 'Tab3Page',
  components: { IonHeader, IonToolbar, IonTitle, IonContent, IonPage, IonSelect, IonItem, IonSelectOption, IonList, IonRow, IonCol, IonButton, }
});
</script>
