<template>
    <div id="button" :class="size" @click="btnEvent()">
        {{btnMessage}}
    </div>
</template>
<script>
import '../../../style/components/button.css'
export default {
    data() {
        return {
            btnMessage: "确定",
            size: "middle"
        }
    },
    methods: {
        btnEvent() {
            alert("点击")
        }
    }
}
</script>




