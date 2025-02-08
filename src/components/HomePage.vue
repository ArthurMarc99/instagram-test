<template>
    <div class="flex justify-center">
        <TopBar/>
    </div>
    <div class="flex justify-center">
        <AvailableContacts/>
    </div>
    <div class="flex justify-center">
        <FeedContent/>
    </div>
    <footer class="mt-auto flex justify-center">
        <NavigationBar/>
    </footer>
</template>

<script setup>
import TopBar from './TobBar.vue';
import AvailableContacts from './AvailableContacts.vue';
import FeedContent from './FeedContent.vue';
import NavigationBar from './NavigationBar.vue';
</script>