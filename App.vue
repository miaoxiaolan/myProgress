<template>
    <div>
        <xx-progress :percentage="70" :show-text='false'/>
        <xx-progress :percentage="40" status='success' color='orange'/>
        <xx-progress :percentage="80" status='exception'/>


        <xx-progress :stroke-width='18' :percentage="80" status='success' :text-inside='true'/>
        <br>
        <xx-progress :percentage='80' type='circle'/>
        <xx-progress :percentage='24' type='circle' status='success'/>
        <xx-progress :percentage='54' type='circle' status='exception'/>
    </div>
</template>

<script>
import  xxProgress  from "./Progress";
export default {
    components: {
        xxProgress
    }  
}
</script>