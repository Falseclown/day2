<template>
    <div class="wrapper">
        <div class="header">
            头部
        </div>
         <div class="main">
            
        </div>
        <div class="footer">
            尾部
        </div>
       
    </div>
</template>
<script>
export default {
    props:{

    },
    components:{

    },
    data(){
        return {

        }
    },
    computed:{

    },
    methods:{

    },
    created(){

    },
    mounted(){

    }
}
</script>
<style scoped lang="scss">
    .wrapper{
        width: 100%;
        height: 100%;
        display: flex;
        flex-direction: column;
        .header{
            width: 100%;
            height: 45px;
            background: pink;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .main{
            width: 100%;
            flex: 1;
        }
         .footer{
            width: 100%;
            height: 45px;
            background: pink;
            display: flex;
            justify-content: center;
            align-items: center;
        }
    }
</style>