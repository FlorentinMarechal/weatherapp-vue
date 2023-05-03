<template>
    <div class="weather-container">
        <div class="weather-wrap">
            <div class="search-box">
                <input type="text" placeholder="Search..." class="search-bar" v-model="query" v-on:keypress="fetchWeather" />
            </div>
            
        </div>
    </div>
</template>

<script>

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
