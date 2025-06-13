<template>
    <div class="figma-page">
        <!-- 顶部Banner -->
        <div class="banner">
            <!-- <img src="/assets/figma/wechat_img527.png" alt="banner" class="banner-img" /> -->
            <div class="banner-title">通讯变更</div>
        </div>
        <!-- 步骤提示 -->
        <div class="step-hint">
            <span class="hint-text">操作步骤提示</span>
            <!-- <img src="/assets/figma/arrow_down.svg" alt="arrow" class="arrow-icon" /> -->
        </div>
        <!-- 步骤三卡片 -->
        <div class="step-card">
            <div class="step-title">步骤三：确认信息</div>
            <div class="info-row">
                <span class="label">通讯地址</span>
                <span class="value">北京市丰台区石榴中心</span>
            </div>
            <div class="info-row">
                <span class="label">邮编</span>
                <span class="value">100000</span>
            </div>
            <div class="info-row">
                <span class="label">手机号</span>
                <span class="value">17600111170</span>
            </div>
            <div class="info-row">
                <span class="label">固话电话</span>
                <span class="value">400-69-12345</span>
            </div>
            <div class="info-row">
                <span class="label">电子邮箱</span>
                <span class="value">lailai@hqins.cn</span>
            </div>
            <div class="info-row">
                <span class="label">非大陆手机号</span>
                <span class="value">+852 38922699</span>
            </div>
            <div class="more-arrow">
                <!-- <img src="/assets/figma/arrow_down.svg" alt="更多" /> -->
            </div>
        </div>
        <!-- 底部按钮 -->
        <div class="footer-btns">
            <div class="btn back">
                <!-- <img src="/assets/figma/avatar.svg" alt="返回" class="avatar" /> -->
                <span>返回/修改</span>
            </div>
            <div class="btn confirm">
                <!-- <img src="/assets/figma/confirm_btn.svg" alt="确认" class="confirm-icon" /> -->
                <span>确认</span>
            </div>
        </div>
    </div>
</template>

<script setup>
// 此处可根据需要添加交互逻辑
</script>

<style scoped>
.figma-page {
    background: #f3f6fa;
    min-height: 100vh;
    font-family: 'PingFang SC', Arial, sans-serif;
}

.banner {
    position: relative;
    width: 100%;
    height: 175px;
    background: #fff;
}

.banner-img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}

.banner-title {
    position: absolute;
    left: 50%;
    top: 60%;
    transform: translate(-50%, -50%);
    font-size: 34px;
    font-weight: 500;
    color: #333;
}

.step-hint {
    display: flex;
    justify-content: flex-end;
    align-items: center;
    margin: 20px 30px 0 0;
}

.hint-text {
    color: #0088ff;
    font-size: 28px;
    margin-right: 8px;
}

.arrow-icon {
    width: 30px;
    height: 30px;
}

.step-card {
    background: #fff;
    border-radius: 20px;
    margin: 30px 20px;
    padding: 30px 20px;
    box-shadow: 0 6px 10px 0 rgba(243, 246, 250, 0.8);
}

.step-title {
    font-size: 28px;
    font-weight: 500;
    color: #333;
    margin-bottom: 20px;
}

.info-row {
    display: flex;
    align-items: center;
    margin-bottom: 16px;
}

.label {
    width: 120px;
    color: #666;
    font-size: 30px;
}

.value {
    color: #333;
    font-size: 30px;
    margin-left: 20px;
}

.more-arrow {
    display: flex;
    justify-content: center;
    margin-top: 10px;
}

.footer-btns {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin: 40px 40px 0 40px;
}

.btn {
    display: flex;
    align-items: center;
    background: #fff;
    border-radius: 100px;
    padding: 10px 30px;
    font-size: 30px;
    font-weight: 400;
    box-shadow: 0 2px 8px rgba(0, 136, 255, 0.1);
    cursor: pointer;
}

.btn.back {
    color: #0088ff;
}

.btn.confirm {
    color: #fff;
    background: linear-gradient(90deg, #0099ff 0%, #0088ff 100%);
}

.avatar {
    width: 40px;
    height: 40px;
    margin-right: 10px;
}

.confirm-icon {
    width: 40px;
    height: 40px;
    margin-right: 10px;
}
</style>
