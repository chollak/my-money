<template>
  <section>
    <status-block></status-block>
    <add-form></add-form>
    <sort-block></sort-block>
    <list-item></list-item>
  </section>
</template>

<script>
import AddForm from '~/components/AddForm';
import ListItem from '~/components/ListItem';
import StatusBlock from '~/components/Status';
import SortBlock from '~/components/SortNav';
import EditForm from '~/components/EditForm';

export default {
  components:{
    AddForm,
    ListItem,
    StatusBlock,
    SortBlock,
    EditForm
  }
};
</script>

<style>
</style>
