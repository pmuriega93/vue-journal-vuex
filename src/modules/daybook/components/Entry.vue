<template>
  <div class="entry-container mb-3 pointer p-2"
  @click="$router.push({name: 'entry', params: { id: 10}})">
      <div class="entry-title d-flex">
          <span class="text-success fs-5 fw-bold">15</span>
          <span class="mx-1 fs-5">julio</span>
          <span class="mx-2 font-weigth-light">2021</span>
      </div>

      <div class="entry-description">
          Exercitation do mollit irure dolore cupidatat. Aliqua do enim ea et irure nulla labore labore consequat. Enim enim elit veniam commodo elit est mollit anim sunt. Occaecat pariatur est in veniam ex ipsum in labore ipsum excepteur. Aliquip enim est Lorem et culpa ad exercitation eiusmod magna irure ex esse. Minim aliqua ut cillum eiusmod amet tempor velit aute non mollit occaecat. Veniam nulla cillum id amet minim mollit aute reprehenderit nostrud esse commodo.
      </div>
  </div>
</template>



<style lang="scss" scoped>
.entry-container {
    border-bottom: 1px solid #2c3e50;
    transition: 0.2s all ease-in;

    &:hover {
        background-color: lighten($color: grey, $amount: 45);
        transition: 0.2s all ease-in;
    }
    .entry-description {
        font-size: 12px;
    }
}
</style>