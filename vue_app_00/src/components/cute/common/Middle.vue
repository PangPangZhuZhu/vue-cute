<template>
    <div class="container">
        <div class="good-item">
            <img src="../../../assets/meat/maodu.jpg" alt="">
            <i></i>
            <div class="info">
                <h4>鸿运毛肚</h4>
                <span class="now">¥58</span>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    data(){
        return{

        }
    }
}
</script>

<style scoped>
.container{
    display:flex;/*弹性布局*/
    flex-wrap:wrap;/*子元素换行*/
    justify-content:center;
    padding:4px;
    overflow:hidden;
}
.good-item{
    width:94%;
    display:flex;/*弹性布局*/
    flex-direction:column;/*方向按列*/
    min-height:268px;
    overflow:hidden;
    position:relative;
}
.good-item img{
    width:100%;
    overflow:hidden;
}
.info{
    width:100%;
    height:20%;
    color:#fff;
    padding:0 8px;
    background-color:rgba(0, 0, 0, 0.3);
    display:flex;
    flex-direction:row;
    justify-content: space-between;
    align-items: center;
    position:absolute;
    bottom:0;

}
.info h4{
    font-weight:bold;
}
</style>

