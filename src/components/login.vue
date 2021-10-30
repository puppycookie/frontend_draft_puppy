<template>
    <div class="login_container">
        <div class="login_box">
            <div class="avatar_box">
                <img src="../assets/xiaogougou.png" alt="">
            </div>
        </div>
    </div>
</template>

<script>
</script>

<style lang="less" scoped>
.login_container {
    background-color: #22476d;
    height: 100%;
}

.login_box {
    width: 450px;
    height: 300px;
    background-color: #fff;
    border-radius: 10px;
    position: absolute;
    left: 50%;
    top: 50%;
    transform: translate(-50%,-50%)
}
.avatar_box {
    height: 130px;
    width: 130px;
    border: 1px solid #eee;
    border-radius: 50%;
    padding: 10px;
    box-shadow: 0 0 15px rgb(166, 164, 168);
    position: absolute;
    left: 50%;
    transform: translate(-50%,-50%);
    background-color: #fff;
        img {
            height: 100%;
            width: 100%;
            border-radius: 50%;
        }
    }
</style>
