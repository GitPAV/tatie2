<template>
      <div class="club-page-main">
        <HeaderClub/>
        <InfoComponent/>  
    </div>
</template>

<script>
    import HeaderClub from '@/app/components/club-page/components/header/header-component.vue'
    import InfoComponent from '@/app/components/club-page/components/infos-component/infos-component.vue'

    export default {
        name: 'Header',
        components: {
            HeaderClub, 
            InfoComponent
        },
    }
</script>

<style>
</style>
