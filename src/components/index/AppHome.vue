<template>
    <div class="app-home">
        <app-header></app-header>
        <app-banner></app-banner>
        <app-listType></app-listType>
    </div>
</template>

<script>
import AppHeader from './AppHeader'
import AppBanner from './AppBanner'
import AppListType from './AppListType'
export default {
    name: 'app-home',
    components:{
        AppHeader,AppBanner,AppListType
    }
}
</script>

<style>

</style>