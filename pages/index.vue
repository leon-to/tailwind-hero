<template>
  <div class="flex flex-col h-screen">
    <top-nav-bar/>
    <div class="flex flex-row w-full h-full">  
      <side-nav-bar class="flex-0 w-40 bg-yellow-500 h-full" />
      <div class="flex flex-col w-full h-full">
        <tag-banner class="h-10 bg-green-300"/>
        <content-list class="flex-0 h-full w-full bg-red-400"/>
      </div>
    </div>
  </div>
</template>
