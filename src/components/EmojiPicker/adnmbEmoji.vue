<template>
    <a class="emoji-item">
        {{data.name}}
    </a>
</template>

<script>
export default {
    name: 'adnmbEmoji',
    props: {
        data: { 
            type: Object 
        },
    },
}
</script>
