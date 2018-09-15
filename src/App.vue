<template>
    <div class="container">
        <div class="columns is-mobile">
            <section class="column">
                <div class="content">
                    <a href="http://vuejs.org">
                        <figure class="image">                    
                            <img src="./assets/vuejs2.jpg" alt="" height="280px" >
                        </figure>
                    </a>
                </div>
            </section>
            <section class="column">
                <div class="content">
                    <a href="https://bulma.io">
                        <figure class="image">
                            <img src="./assets/bulma2.png" alt="">
                        </figure>
                    </a>  
                </div>
            </section>
        </div>
        <section class="section">
            <p class="subtitle is-2">template for vuejs with bulma</p>
        </section>
        <section class="section">
            <p class="subtitle is-4">Download
                <a href="">
                    <i class="fab fa-github"></i>
                </a>     
            </p>
        </section>
        
<!--         
        <section class="section">
            <div class="columns is-mobile">
                <div class="column">
                    <div class="box">
                        <a href="http://vuejs.org">
                            <figure class="image is-128x128">                    
                                <img src="./assets/vuejs2.jpg" alt="" height="280px" >
                            </figure>
                        </a>
                    </div>
                </div>
                <div class="column">
                    <div class="box">
                        <a href="">
                            <figure class="image">
                                <img src="./assets/bulma.png" alt="">
                            </figure>
                        </a>  
                    </div>              
                </div>
            </div>
        </section>
        <div class="columns">
            <div class="column is-three-fifths is-offset-one-fifth">
                <p>View source on github</p>
                <figure class="image is-48x48">
                    <img src="./assets/github.png" alt="">
                </figure>
            </div>
        </div>
        <div class="tile"></div>         -->
    </div>
</template> 

<script>
export default{
    name: "App"
}
</script>

<style>
section{
    text-align: center;
}
/*
.columns{
    border: 1px solid;
}
.column{
    border: 1px dashed red;
    height: 350px;
}

section.columns.column{
    position: relative;
    display: flex;
    justify-content: center;
    align-items: center;
}


section.columns.column > .box{
    top: 50%;
    position: absolute;
    flex: 1;
    display: flex;
    justify-content: center;
}
.image{
    flex: 1;
    
}
*/
</style>
