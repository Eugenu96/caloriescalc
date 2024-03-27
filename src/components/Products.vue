<script setup>
import { ref } from 'vue'
</script>

<template>
    <div class="search-area">
        <h1 class="search-area_title">Products</h1>
        <div class="search">
            <input type="text" class="input search_input" />
            <div class="button search-button">Search</div>
        </div>
    </div>

    <details class="search-res hidden">
        <summary>Search result</summary>
        <div>
            <p>item</p>
            <p>item</p>
            <p>item</p>
        </div>
    </details>

    <h1>New products</h1>
    <form action="" method="post">
        <!-- <input type="text" name="pr_name" class="pr-form-input"> -->
        <textarea class="input textarea-input" name="" placeholder="Enter product name..."></textarea>
        <div class="input-gr">
            <input type="number" name="calories" class="input input-gr_item" id="">
            <input type="number" name="carbohydrates" class="input input-gr_item" id="">
            <input type="number" name="protein" class="input input-gr_item" id="">
            <input type="number" name="fat" class="input input-gr_item" id="">
        </div>

        <div class="input-gr">
            <input type="number" name="number" class="input input-gr_item" id="">
            <div class="input-gr_item radio-button radio-button-active">
                <div class="radio-button_background">weight/gram</div>
            </div>
            <div class="input-gr_item radio-button">
                <div class="radio-button_background">units</div>
            </div>
        </div>

        <!-- <input type="radio" name="number_type" id="radio_weight">
                        <label for="radio_weight">weight/gram</label>
                        <input type="radio" name="number_type" id="radio_units">
                        <label for="radio_units">units</label> -->

        <!-- <input type="submit"> -->
        <div class="button button-submit"> Add </div>
    </form>

</template>

<style lang="scss">
.search-area {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 2px 5px;
}

.search-area_title {
    font-size: 1.2em;
}

.search {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.search_input {}

.search-res {}
</style>