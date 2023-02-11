<template>
    <div class="todoListContainer">
        <div class="heading">
            <h2 id="title">To Do List</h2>
            <add-item /> 
        </div>
        <list-view />
    </div>
</template>

<script>
.import addItem from "./addItem"
import listView from "./listView"
export default {
    components:{
        addItem,
        listView
    }
}


</script>

<style scoped>
.todoListContainer {
    width: 350px;
    margin: auto;
}
.heading{
    background: #e6e6e6;
    padding: 10px;
}
#title{
    text-align: center;
    
}
</style>