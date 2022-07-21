<template>
    <div class="container">
        <div id="jumbotron">
            <div>
                <div>&lt;<span>title</span>&gt;</div>
                <p>Hi, this is my first Vue.js component</p>
                <div>&lt;/<span>title</span>&gt;</div>
            </div>
        </div>
    </div>
</template>

<script>
export default{
    name: 'Jumbo',
}
</script>

<style scoped>
    .container{
        text-align: center;
    }

    #jumbotron{
        display: inline-block;
        padding: 30px;
        color: #D2D2D2;
        border-radius: 5px;
        background-color: #1E1E1E;
        text-align: left;
    }


    #jumbotron div div{
        color: #7C7C7C;
    }

    #jumbotron span{
        color: #5394CB;
    }
</style>