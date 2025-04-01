<template>
  <div class="card-poem">
    <poemasList/>
    <poemasList/>
    <poemasList/>
    <PoesiaOlvidada/>
    <SiemprePoeta/>
    <PoesiaOlvidada/>
    <SiemprePoeta/>
    <SiemprePoeta/>
    <poemasList/>
    <poemasList/>
    <PoesiaOlvidada/>
    <SiemprePoeta/>
  </div>
</template>



<script setup>
import poemasList from './poemasList.vue';
import PoesiaOlvidada from './PoesiaOlvidada.vue';
import SiemprePoeta from './SiemprePoeta.vue';
</script>

<style>
.card-poem{
    width: 100%;
    display: flex;
    flex-wrap: wrap;
}
</style>