<template>
    <div id = "bar">
        <nav id = "title">
            <div class="elem"> PostApp</div>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Login</a></li>
                <li><a href="#">Signup</a></li>
            </ul>
        </nav>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css2?family=Open+Sans&family=Roboto&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Lobster&display=swap');

#bar
{
    color: blue;
    font-size: 14px;
    background-color:#45AAF2;
    size: 350px;
    border: 3px #45AAF2;
    border-radius: 5px;
    height: auto    ;
    display: flex;

}
#title
{
    text-align: left;
}
.elem
{
    font-family: 'Lobster', cursive;
    color: #FBFBFB;
    text-align: left;
    font-size: 30px;
}
ul
{
    font-family: 'Open Sans', sans-serif;
    font-family: 'Roboto', sans-serif;
    color: #FBFBFB;
    margin-right: 80px;
}
nav li
{
    list-style-type: none;
    margin-right: 15px;
}
nav a 
{
    font-family: 'Roboto', sans-serif;
    color: #FBFBFB;
    text-decoration: none;
    font-size: 25px;
}
nav a:hover 
{
    color:#878787;
}
</style>