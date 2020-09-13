<template>
<div id="app">
    <div class="flex flex-col min-h-screen lg:max-w-screen-lg lg:m-auto">
      <main class="flex-1">
        <div class="flex flex-col px-3 py-7">
            <div class="text-center">
                <img class="inline h-24 w-24 rounded-38px" src="@/assets/images/profilePhoto.png" alt="Rodney Cotton">
                <p class="font-montserrat font-semibold text-sm leading-4 text-gray-1 mt-3 lg:text-2xl lg:leading-8">Rodney Cotton</p>
                <p class="font-montserrat font-semibold text-xxs leading-3 text-gray-2 mt-1 lg:text-sm lg:mt-2 lg:leading-4">Helsinki, Finland</p>
            </div>
            <div class="flex items-center justify-center mt-4 lg:mt-6">
                <div class="w-24 py-2 bg-gray-3 rounded-xl lg:py-4">
                    <p class="font-montserrat font-semibold text-xs leading-4 text-center text-gray-1 lg:text-lg lg:leading-5">100</p>
                    <p class="font-montserrat font-semibold text-xs leading-4 text-center text-gray-1 lg:text-sm">Posts</p>
                </div>
                <div class="w-24 py-2 ml-3 bg-gray-3 rounded-xl lg:py-4">
                    <p class="font-montserrat font-semibold text-xs leading-4 text-center text-gray-1 lg:text-lg lg:leading-5">2,242</p>
                    <p class="font-montserrat font-semibold text-xs leading-4 text-center text-gray-1 lg:text-sm">Followers</p>
                </div>
                <div class="w-24 py-2 ml-3 bg-gray-3 rounded-xl lg:py-4">
                    <p class="font-montserrat font-semibold text-xs leading-4 text-center text-gray-1 lg:text-lg lg:leading-5">1,432</p>
                    <p class="font-montserrat font-semibold text-xs leading-4 text-center text-gray-1 lg:text-sm">Following</p>
                </div>
            </div>
            <div class="mt-10">
                <div class="imgGrid grid grid-rows-3 grid-cols-3 gap-3">
                    <div>
                        <img class="rounded-3xl" src="@/assets/images/photo1.png" alt="Bedroom">
                    </div>
                    <div class="col-span-2">
                        <img class="rounded-3xl" src="@/assets/images/photo2.png" alt="Sofa">
                    </div>
                    <div class="col-span-2">
                        <img class="rounded-3xl" src="@/assets/images/photo3.png" alt="Bath">
                    </div>
                    <div class="row-span-2">
                        <img class="rounded-3xl" src="@/assets/images/photo4.png" alt="Lamp">
                    </div>
                    <div>
                        <img class="rounded-3xl" src="@/assets/images/photo5.png" alt="Plant">
                    </div>
                    <div>
                        <img class="rounded-3xl" src="@/assets/images/photo6.png" alt="Table">
                    </div>
                </div>
            </div>
        </div>
      </main>
        <footer class="mt-6 md:pb-6">
          <div class="flex justify-center flex-col items-center">
          <div class="border-t border-gray-2 w-64 text-center"></div>
          <p class="font-montserrat text-sm font-semibold leading-6 text-gray-2 text-center py-2">Nisarg Patel @ DevChallenges.io</p>
          </div>
        </footer>
    </div>
</div>
</template>

<script>
export default {
    name: 'App',
    components: {}
}
</script>

<style lang="scss">
#app {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
}

.imgGrid {
    // .i2{
    //   grid-column: 2/4;
    // }
}
</style>
