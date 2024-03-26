<script>
import { ref } from 'vue';
</script>

<template>
    <div class="status-bar">
        <div class="status-bar_section">
            <div class="status-bar_section_title">Calories</div>
            <div class="status-bar_section_bar">
                <div class="status-bar_section_bar_fill">10%</div>
            </div>
        </div>
        <div class="status-bar_section">
            <div class="status-bar_section_title">Protein</div>
            <div class="status-bar_section_bar">
                <div class="status-bar_section_bar_fill">10%</div>
            </div>
        </div>
        <div class="status-bar_section">
            <div class="status-bar_section_title">Carbohydrates</div>
            <div class="status-bar_section_bar">
                <div class="status-bar_section_bar_fill">10%</div>
            </div>
        </div>
        <div class="status-bar_section">
            <div class="status-bar_section_title">Fat</div>
            <div class="status-bar_section_bar">
                <div class="status-bar_section_bar_fill">10%</div>
            </div>
        </div>
    </div>
</template>

<style lang="scss">
@import '../variables.scss';

.status-bar {
    margin: 5px 0;
    padding: 5px 0;
    width: 100%;
    display: flex;
    justify-content: space-around;
    align-items: center;
    background-color: $default_color;
}

.status-bar_section {
    width: 20%;
    align-items: center;
}

.status-bar_section_title {
    color: $grey;
    margin-bottom: 2px;
}

.status-bar_section_bar {
    background-color: $grey;
    width: 100%;
}

.status-bar_section_bar_fill {
    background-color: $status-bar_color;
    background-color: orange;
    width: 10%;
    padding: 2px 2px;
}
</style>