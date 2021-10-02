<template>
  <div id="app">
    <TodoHeader/>
    <TodoInput/>
    <TodoList/>
    <TodoFooter/>
  </div>
</template>

<script>
import TodoHeader from './components/TodoHeader'
import TodoInput from './components/TodoInput'
import TodoList from './components/TodoList'
import TodoFooter from './components/TodoFooter'


export default {
  name: 'App',
  components: {
    //컴포넌트 태그명 : 컴포넌트 내용
    TodoHeader,
    TodoInput,
    TodoList,
    TodoFooter
    //단어 앞자리가 대문자 = 파스칼 케이스(컴포넌트) / 케밥기법(템플릿)
  }
}
</script>

<style>
  body{
    text-align: center;
    background-color: #f6f6f6 ;
  }
  input{
    border-style: groove ;
    width: 200px;
  }
  button{
    border-style: groove;
  }
  .shadow {
    box-shadow: 5px 10px 10px rgba(0, 0, 0, 0.03);
  }

</style>
