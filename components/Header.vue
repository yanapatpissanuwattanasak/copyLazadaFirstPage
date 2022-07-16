<template>
<div class="header">
    <button class="button-logo"> </button>
    <div class = "search-bar flex justify-end" >
        <input class= "input-search" placeholder="search"></input>
        <button class="button-red-blue "><a href='https://www.youtube.com/watch?v=c2jLUu9OolQ&list=RDc2jLUu9OolQ&start_radio=1' >asdasd</a></button>
    </div>
    
</div>

</template>

<style lang="css">
    .button-logo {
        height: 48.8px;
        width: 200px;
        margin-top: auto;
        margin-bottom: auto;
        display: flex;
        align-items: center;
        justify-items: center;
        background: rgb(211, 210, 210);
    }
    .search-bar {
        height: 48.8px;
        width: 688px;
        margin-top: auto;
        margin-bottom: auto;
        /* background: green; */
        display: flex;
    }
    .input-search {
        padding: 20px;
        width: 688px;
        display: flex;
        background: rgb(236, 235, 235);
        margin-right: 20;
    }
    .button-red-blue {
    width: 45px;
    height: 45px;
    text-indent: -9999px;
    border: none;
    border-radius: 0 2px 2px 0;
    outline: none;
    background: #f8b087 ;
    background-size: 22px;
    box-shadow: none;
    cursor: pointer;
    margin-top: auto;
    margin-bottom: auto;
    padding-left: 20px;
    
}
.button-red-blue:hover {
    width: 45px;
    height: 45px;
    text-indent: -9999px;
    border: none;
    border-radius: 0 2px 2px 0;
    outline: none;
    background: #f57224 ;
    background-size: 22px;
    box-shadow: none;
    cursor: pointer;
    margin-top: auto;
    margin-bottom: auto;
    padding-left: 20px;
}
</style>