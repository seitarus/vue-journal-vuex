<template>
    <div class="entry-container mb-3 pointer p-2"
        @click="$router.push({name: 'entry', params: { id: 10 } })">
        
        <!-- Titulo -->
        <div class="entry-title d-flex">
            <span class="text-success fs-5 fw-bold">20</span>
            <span  class="mx-1 fs-5">Abril</span>
            <span  class="mx-2 fw-light">2022, Miércoles</span>
        </div>

        <div class="entry-description">
            Aute cupidatat nulla dolore commodo. Amet reprehenderit anim cillum minim voluptate dolor cupidatat sint. Sunt consequat et esse tempor nulla quis velit. In reprehenderit Lorem aute et cillum labore in est incididunt esse.
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
.entry-container {
    border-bottom: 1px solid #2c3e50;
    transition: 0.2s all ease-in;

    &:hover{
        background-color: lighten($color: grey, $amount: 45);
        transition: 0.2s all ease-in;
    }
}

.entry-description {
    font-size: 12px;
}

</style>