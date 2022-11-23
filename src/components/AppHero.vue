<script>
export default {
  data() {
    return {
      title:'Ha Bootstrap!!!!',
      text: 'Lorem ipsum, dolor sit amet consectetur adipisicing elit. Corrupti rem nihil itaque officiis nostrum quisquam voluptatibus debitis tempora! Rerum, unde illo. Consequuntur odit reiciendis voluptas tenetur minus odio veritatis blanditiis.'
    }
  }
}
</script>

<template>
    <div class="jumbotron jumbotron-fluid">
        <div class="container">
            <h2 class="display-4 mt-3">{{ title }}</h2>
            <p class="lead">{{ text }}</p>
            
        </div>
    </div>
</template>

<style scoped>
h1 {
  text-align: center;
}
</style>