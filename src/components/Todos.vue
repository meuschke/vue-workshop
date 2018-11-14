<template>
  <div class="todos">
    <div>
      <h2>My To Do List</h2>
      <input type="text" placeholder="Title...">
      <button>Add</button>
    </div>

    <ul class="list">
      <li>
        <label>
          <input type="checkbox" value="Hit the gym" />
          Hit the gym
        </label>
      </li>
      <li>
        <label>
          <input type="checkbox" checked value="Pay bills" />
          Pay bills
        </label>
      </li>
      <li>
        <label>
          <input type="checkbox" value="Buy eggs" />
          Buy eggs
        </label>
      </li>
      <li>
        <label>
          <input type="checkbox" value="Read a book" />
          Read a book
        </label>
      </li>
      <li>
        <label>
          <input type="checkbox" value="Organize office" />
          Organize office
        </label>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Todos'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.list {
  list-style: none;
}
</style>
