<template>
  <div id="app" class="container">
    <hr />
    <div class="uk-flex-center">
      <div class="task-header">
        <div class="uk-card uk-card-default uk-card-small uk-card-body">
          <h3 class="uk-card-title">New Todo</h3>
          <div class="uk-margin">
            <input
              class="uk-input uk-form-width-medium uk-form-small"
              type="text"
              placeholder="Add Task"
            />
          </div>
          <button class="uk-button uk-button-secondary uk-button-small">Save</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "app"
};
</script>
<style scoped>
.uk-card-body {
  padding: 12px 30px;
}
.icons .fa {
  padding: 0 2px;
}
.task-header {
  text-align: center;
  margin-top: 10px;
}
</style>
