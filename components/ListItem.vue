<template>
  <ul class="list-group">
    <li class="list-group-item">
      <div class="row">
        <div class="col">
          <blockquote class="blockquote">
            <p class="mb-0">
              Lays
              <b>7000</b>
            </p>
            <footer class="blockquote-footer">10-05-2020</footer>
          </blockquote>
        </div>
        <div class="col text-right">
          <span class="badge badge-primary badge-pill mr-1">¶</span>
          <span class="badge badge-danger badge-pill">X</span>
        </div>
      </div>
      <edit-form></edit-form>
    </li>
  </ul>
</template>

<script>
import EditForm from '~/components/EditForm';
export default {
  components:{
    EditForm
  }
};
</script>

<style>
</style>