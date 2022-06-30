<script>
    export default{
        data()
        {
            return{
                count: 0
            }
        },
        methods:{
            increment()
            {
                this.count+=5;
            }
        }
    }
</script>

<template>

    <section>
        <div class="nav-wrapper bg-primary">
            <div>
                <ul class="nav-links oswald">
                    <li><a class="text-light">Home</a></li>
                    <li><a href="" class="text-light">About</a></li>
                    <li><a href="" class="text-light">NetFan</a></li>
                </ul>
            </div>
            <form method="GET" action="">
                <div class="nav-attr">
                    <input type="text" name="" id="">
                    <button class="oswald">Search</button>
                </div>        
            </form>
            <div>
                <form action="">
                    <button type="submit">Login</button>
                </form>
            </div>
        </div>
    </section>

</template>

<script>

</script>

<style>
@import "../assets/base.css";
.nav-wrapper{
    display: flex;
    padding-top: 10px;
    padding-bottom: 10px;
    padding-left: 30px;
    padding-right: 30px;
    justify-content: space-around;
}
.nav-links > li{
    display: inline;
    margin: 10px;
}
.nav-links > li > a{
    text-decoration: none;
}
.nav-attr{
    margin: 0;
}
.nav-attr > *{
    border-radius: 10px;
    border-color: transparent;
}
.nav-attr > button{
    margin-left: 10px;
}

</style>
