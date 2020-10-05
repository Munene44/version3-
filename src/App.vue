<template>
  <div id="app">
    <Todos/>
  </div>
</template>

<script>
import Todos from './components/Todos';

export default {
  name: 'App',
  components: {
    Todos
      },
  data(){
    return{
      todo:[
      {
        id: 1,
        title: "Todo one",
        completed: false
      },
      {
        id: 1,
        title: "Todo two",
        completed: true
      },
      {
        id: 1,
        title: "Todo one",
        completed: false
      }
      ]
    }
  }
}
</script>

<style>
  * {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }
  body{
    font-family: Arial, Helvetica, sans-serif;
    line-height: 1.4;
  }
</style>
