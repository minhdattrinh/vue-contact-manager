<template>
  <div class="container mt-3">
    <div class="row">
      <div class="col">
        <p class="h3 text-success fw-bold">
          Contact Manager
          <router-link to="/contacts/add" class="btn btn-success btn-sm"
            ><i class="fa fa-plus-circle">New</i></router-link
          >
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Contact-manager",
};
</script>

<style></style>
