<script setup>
import { ref } from 'vue'
</script>

<template>
    <div class="nav-horizontal">
        <div class="logo">CaloriesCalc</div>
        <div class="nav-group">
            <a href="" class="nav-link">link</a>
            <a href="" class="nav-link">link</a>
            <a href="" class="nav-link">link</a>
            <a href="" class="nav-link">link</a>
            <a href="" class="nav-link">link</a>
        </div>
    </div>
</template>

<style lang="scss">
@import '../variables.scss';

.logo {
    margin: 5px 5px;
    // font-size: 1.5em;
    color: $primary-color;
}

.nav-horizontal {
    display: flex;
    width: 100%;
    justify-content: space-between;
    align-items: center;
    background-color: $default-color;
    color: $grey2;
    font-size: 1.5em;

    .nav-link {
        color: $grey2;
    }

    .nav-link:hover {
        color: $primary-color;
    }
}

.nav-group {
    width: 60%;
    display: flex;
    padding: 0 5px;
    float: right;
    justify-content: space-around;
    align-items: center;

}

.nav-link {
    margin: 0 2px;
    text-decoration: none;
}
</style>