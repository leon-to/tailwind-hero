<template>
  <div class="flex h-screen">
    <top-nav-bar class="flex-0 w-16 h-full"/>
    <side-nav-bar class="flex-0 w-32" />
    <content-list class="flex-0 w-64"/>
  </div>
</template>

<script>
import ContentList from '~/components/ContentList.vue'
import TopNavBar from '~/components/TopNavBar.vue'
import SideNavBar from '~/components/SideNavBar.vue'

export default {
components: { TopNavBar, SideNavBar, ContentList },
  name: 'IndexPage'
}

</script>
