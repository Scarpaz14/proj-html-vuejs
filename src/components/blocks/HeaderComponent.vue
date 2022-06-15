<template>
    <header>
        <div class="container">
            <div class="row">
                <div class="col">
                    <Navbar/>
                </div>
            </div>
        </div>
    
    </header>
</template>

<script>
import Navbar from '../commons/NavBar.vue'
export default {
    name:'HeaderComponent',
    components:{
        Navbar
    }

}
</script>

<style lang="scss" scoped>

header{
    background-color: #1f1f52;
    padding: 20px 0;
}

</style>