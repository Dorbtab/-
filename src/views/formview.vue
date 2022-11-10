<template>
    <div>
        <button class="p-2 bg-slate-400 " @click="dropdown=!dropdown">menu</button>
        <div class="rounded-lg bg-red-400 animate-fadeIn" v-if="dropdown">
            this is dropdown
        </div>
    </div>
</template>

<script>
    export default {
        data()
        {
            return{
                count: 0,
                dropdown: false,
                name: "Doe"
            }
        }
    }
</script>

<style>

</style>