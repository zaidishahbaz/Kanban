<template>
  <div>
    <h3 align="center" class="uk-heading-divider">Kanban Board</h3>
    <div class="uk-grid-medium uk-child-width-expand@s uk-text-center" uk-grid>
      <BoardColumn name="ToDO" />
      <BoardColumn name="InProgress" />
      <BoardColumn name="Done" />
    </div>
  </div>
</template>
<script>
import BoardColumn from "./BoardColumn";
export default {
  name: "Board",
  components: {
    BoardColumn
  }
};
</script>