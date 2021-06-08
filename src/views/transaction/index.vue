<template>
  <div class="container my-5">
    <div class="row justify-content-center">
      <div class="col-8">
        <router-link
          :to="{ name: 'transaction.create' }"
          class="btn btn-primary btn-sm rounded mb-3"
        >
          ADD</router-link
        >
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>
