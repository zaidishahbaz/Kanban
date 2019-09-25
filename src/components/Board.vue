<template>
  <div>
    <h3 align="center" class="uk-heading-divider">Kanban Board</h3>
    <div class="uk-grid-medium uk-child-width-expand@s uk-text-center" uk-grid>
      <div>
        <div class="uk-card uk-card-default uk-card-body" id="todo-col">
          <h3>Todo</h3>
          <div class="uk-alert-default" uk-alert>
            <p>Learn Node</p>
            <div class="has-text-centered icons">
              <button class="uk-button uk-button-primary uk-button-small">Edit</button>
              <span style="margin:2px"></span>
              <button class="uk-button uk-button-danger uk-button-small">Delete</button>
            </div>
          </div>
        </div>
      </div>
      <div>
        <div class="uk-card uk-card-default uk-card-body" id="in-progress-col">
          <h4>InProgress</h4>
          <div class="uk-alert-default" uk-alert>
            <p>Learn GQL</p>
            <div class="has-text-centered icons">
              <button class="uk-button uk-button-primary uk-button-small">Edit</button>
              <span style="margin:2px"></span>
              <button class="uk-button uk-button-danger uk-button-small">Delete</button>
            </div>
          </div>
        </div>
      </div>
      <div>
        <div class="uk-card uk-card-default uk-card-body" id="done-col">
          <h4>Done</h4>
          <div class="uk-alert-default" uk-alert>
            <p>Learn Mongo</p>
            <div class="has-text-centered icons">
              <button class="uk-button uk-button-primary uk-button-small">Edit</button>
              <span style="margin:2px"></span>
              <button class="uk-button uk-button-danger uk-button-small">Delete</button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Board"
};
</script>