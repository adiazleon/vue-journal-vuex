<!-- eslint-disable vue/multi-word-component-names -->
<template>
  <div
    class="entry-container mb-3 pointer p-2"
    @click="$router.push({name: 'entry', params:{id: 10}})"
  >
    <!-- Titulo -->
    <div class="entry-title d-flex">
        <span class="text-success fs-5 fw-bold">28</span>
        <span class="mx-1 fs-5">Febrero</span>
        <span class="mx-2 fw-light">2023 martes</span>
    </div>
    <div class="entry-description">
        Veniam Lorem aute veniam irure qui velit nostrud amet nulla quis. Nisi qui nisi enim eiusmod sint non cillum proident reprehenderit. Nisi laboris nulla esse adipisicing laborum est nisi labore sit quis minim magna magna exercitation. Sint cillum cillum sint sit eiusmod tempor esse sint aliqua elit ipsum cupidatat in. Laborum amet eiusmod fugiat magna.
    </div>
  </div>
</template>

<style lang="scss" scoped>
.entry-container{
    border-bottom: 1px solid #2c3e50;
    transition: 0.2s all ease-in;

    &:hover{
        background-color: lighten($color: grey, $amount: 45);
    }

    .entry-description{
        font-size: 12px;
    }

}
</style>