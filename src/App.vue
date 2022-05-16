<template>
  <div class="container">
    <h1>Rick and monty</h1>
    <FilterByStatus/>
    <FilerByName/>
       <ListCharacters/> 
</div>
</template>

<script>
import ListCharacters from "./components/ListCharacters"
import FilterByStatus from "./components/FilterByStatus.vue"
import FilerByName from "./components/FilerByName.vue"
export default {
  name: 'App',
  components: {
    ListCharacters,
    FilterByStatus,
    FilerByName
}
}
</script>
<style lang="scss">
:root{
  --background-body: #14294d;
--background-card:#839eee;
--text-white:#FFFFFF;
--text-gray:#c0c0c0;
--text-orange:#FF9800;
}
*{box-sizing:border-box;
margin:0;
padding:0;
}
body{
  background-color: var(--background-body);
  color:var(--text-white);
  font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;

}
h1{
  margin-bottom:3er;
  text-align: center;
}
.container{
 
  width:980px;
max-width: 90%;
margin:5rem auto;

}
img{
  width:100%;
}
</style>
