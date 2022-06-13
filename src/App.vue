<template>
<div>
  <header></header>
  <main>
    <div class="todo-body">
      <div class="todo-header">
        <h1>TODO</h1>
        <img src="/images/icon-sun.svg" alt="">
      </div>
      <div class="todo-input">
        <span>
          <!-- <img src="/images/icon-check.svg" alt="" style="text-align:center"> -->
        </span>
        <input type="text" placeholder="Create a new todo...">
      </div>
      <div class="todo-container">
          <div class="todo-tasks">
          <span></span>
          <p>Complete Online JS Course</p>
          <img src="/images/icon-cross.svg" alt="">
        </div>
        <div class="todo-tasks">
          <span></span>
          <p>Finish Class</p>
          <img src="/images/icon-cross.svg" alt="">
        </div>
        <div class="todo-tasks">
          <span></span>
          <p>Jog around the Park</p>
          <img src="/images/icon-cross.svg" alt="">
        </div>
        <div class="todo-tasks">
          <span></span>
          <p>10 mins meditation</p>
          <img src="/images/icon-cross.svg" alt="">
        </div>
        <div class="todo-tasks">
          <span></span>
          <p>Read for 1 hour</p>
          <img src="/images/icon-cross.svg" alt="">
        </div>
        <div class="todo-tasks">
          <span></span>
          <p>Pick up Groceries</p>
          <img src="/images/icon-cross.svg" alt="">
        </div>
        <div class="todo-state">
          <p>5 items left</p>
          <div class="active">
            <p>All</p>
          <p>Active</p>
          <p>Completed</p>
          </div>
          <p>Clear Completed</p>
        </div>
      </div>
      <footer>Drag and drop to reorder Tasks</footer>
      
    </div>
  </main>
</div>
  
</template>

<script>


export default {
  name: 'App',
  components: {

  }
}
</script>

<style scoped>

</style>
