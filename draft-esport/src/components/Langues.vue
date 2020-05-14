<template>
    <v-section class="flags">
        <div class="pays">
            <v-img  src="../assets/france.png"></v-img>
        </div>
        <div class="pays">
            <v-img src="../assets/uk.png"></v-img> 
        </div>
        <div class="pays">
            <v-img src="../assets/germany.png"></v-img>
        </div>
    </v-section>
</template>

<script>
export default {
  name: 'Langues',
}
</script>


<style>

.flags{
    position: absolute;
    display: flex;
}

.pays{
    margin-left: 10px;
    margin-top: 10px;
    cursor: pointer;
}


</style>
