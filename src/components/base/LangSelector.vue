<template>
    <div class="lang">
        <div class="lang_wrp lang_btn" @click="showChoice = 2">
            <div class="lang_img">👅</div>
        </div>
        <div
            class="lang_wrp choise_wrp"
            :class="{
                first_choice: showChoice === 2,
                hide: showChoice === 3,
            }"
            @click="showChoice = 3"
        >
            <div class="lang_text">EN</div>
        </div>
        <div
            class="lang_wrp choise_wrp"
            :class="{
                second_choice: showChoice === 2,
                hide: showChoice === 3,
            }"
            @click="showChoice = 3"
        >
            <div class="lang_text">UA</div>
        </div>
    </div>
</template>
<script>
export default {
    data() {
        return {
            showChoice: 1,
        }
    },
}
</script>
