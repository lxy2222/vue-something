<template>
   <div>
    <h1>{{msg}}</h1>
    <Button @click="reset">重置</Button>
    </div>
</template>
<script>
    import {Button} from 'iview'
    export default {
        name: 'home',
        components: {
           Button
        },
        data () {
            return {
                msg: '2048小游戏'
            }
        },
        methods:{
            test: function () {
                alert(1111);
            }
        }
    }
</script>