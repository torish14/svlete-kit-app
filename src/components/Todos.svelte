<div class="todoapp stack-large">

  <!-- 新しい Todo -->
  <form>
    <h2 class="label-wrapper">
      <label for="todo-0" class="label__lg">
        What needs to be done?
      </label>
    </h2>
    <input type="text" id="todo-0" class="input input__lg" autocomplete="off">
    <button type="submit" disabled class="btn btn__primary btn__lg">Add</button>
  </form>

  <!-- todos のフィルタリング -->
  <div class="filters btn-group stack-exception">
    <button class="btn toggle-btn" aria-pressed="true">
      <span class="visually-hidden">Show</span>
      <span>All</span>
      <span class="visually-hidden">tasks</span>
    </button>
    <button class="btn toggle_btn" aria-pressed="false">
      <span class="visually-hidden">Show</span>
      <span>Avtive</span>
      <span class="visually-hidden">tasks</span>
   </button>
  </div>

  <!-- todos のステータス -->
  <h2 id="list-heading">2 out of 3 items completed</h2>

  <!-- Todos -->
  <ul class="todo-list stach-large" role="list" aria-labelledby="list-heading">

    <!-- Todo1 （編集モード） -->
    <li class="todo">
      <div class="stack-small">
        <form class="stack-small form-group">
          <div class="form-group">
            <label for="todo-1" class="todo-label">
              New name for 'Create a svelte kit app'
            </label>
            <input type="text" id="todo-1" class="todo-text" autocomplete="off">
          </div>
          <div class="btn-group">
            <button class="btn todo-cancel" type="button">
              Cancel
              <span class="visually-hidden">
                renaming Create a svelte kit app
              </span>
            </button>
            <button class="btn btn__primary todo-edit" type="submit">
              Save
              <span class="visually-hidden">new name for Create a svelte kit app</span>
            </button>
          </div>
        </form>
      </div>
    </li>

    <!-- Todo2-->
    <li class="todo">
      <div class="stack-small">
        <div class="c-cb">
          <input type="checkbox" id="todo-2" checked>
          <label for="todo-2" class="todo-label">
            Create your first component
          </label>
        </div>
        <div class="btn-group">
          <button class="btn" type="button">
            Edit
            <span class="visually-hidden">Create your first component</span>
          </button>
          <button class="btn btn_danger">
            Delete
            <span class="visually-hidden">Create your first component</span>
          </button>
        </div>
      </div>
    </li>

    <!-- Todo3 -->
    <li class="todo">
      <div class="stach-small">
        <div class="c-cb">
          <input type="checkbox" id="todo-3">
          <label for="todo-3" class="todo-label">
            Complete the rest of the tutorial
          </label>
        </div>
        <div class="btn-group">
          <button class="btn" type="button">
            Edit
            <span class="visually-hidden">
              Complete the rest of the tutorial
            </span>
          </button>
          <button class="btn btn__danger">
            Delete
            <span class="visually-hidden">
              Complete the rest of the tutorial
            </span>
          </button>
        </div>
      </div>
    </li>
  </ul>

  <hr>

  <!-- 追加機能-->
  <div class="btn-group">
    <button class="btn btn__primary" type="button">
      Check all
    </button>
    <button class="btn btn__primary" type="button">
      Remove completed
    </button>
  </div>
</div>
