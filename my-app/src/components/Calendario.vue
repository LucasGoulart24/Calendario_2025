<template>
    <div class="Calendario">
        <div class="data">
            <h3>{{ ano }}</h3>
            <h3>{{ data }}</h3>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Calendario',
    data() {
        return {
            ano: '2025',
            data: '24/07/2025'
        }
    }
}
</script>

<style>
.Calendario{
    width: 550px;
    padding: 5px;
    border-radius: 5px;
    background-color: #eee;
}

.data{
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.data h3{
    font-size: 1.5rem;
    font-weight: 400;
}
</style>