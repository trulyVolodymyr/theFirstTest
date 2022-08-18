<template>
    <header class="header">
        <LangSelector />
        <TheLogo />
    </header>
</template>
<script>
import LangSelector from '../base/LangSelector.vue'
import TheLogo from '../base/TheLogo.vue'
export default {
    components: {
        LangSelector,
        TheLogo,
    },
}
</script>
