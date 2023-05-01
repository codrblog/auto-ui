<template>
    <div>
        <ChatHeader />
        <ChatMainArea />
        <ChatFooter />
    </div>
</template>

<script>
import { ChatHeader, ChatMainArea, ChatFooter } from './components/index';

export default {
    name: 'App',
    components: {
        ChatHeader,
        ChatMainArea,
        ChatFooter
    }
}
</script>
