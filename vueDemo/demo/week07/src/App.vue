<template>
    <div>
        <div>插件写法</div>
        <button @click="modal">按钮</button>
    </div>
</template>

<script>
    export default {
        data(){
            return {}
        },
        created(){

        },
        methods:{
			modal(){
				this.$notify('提示消息',{time:1000});
			}
        },
        computed:{

        },
        components:{

        }
    }
</script>

<style scoped>

</style>
