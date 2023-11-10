<template>
<div class="flex ">
    <h2 class="text-2xl font-bold text-gray-900">
        Хотите получать информацию о наших акциях!
    </h2>
    
    <div>
        <label
                for="UserEmail"
                class="relative block overflow-hidden rounded-md border border-gray-200 px-3 pt-3 shadow-sm focus-within:border-blue-600 focus-within:ring-1 focus-within:ring-blue-600"
        >
            <input
                    type="email"
                    id="UserEmail"
                    placeholder="Email"
                    class="peer h-8 w-72 w-full border-none bg-transparent p-0 placeholder-transparent focus:border-transparent focus:outline-none focus:ring-0 sm:text-sm"
            />

            <span
                    class="absolute start-3 top-3 -translate-y-1/2 text-xs text-gray-700 transition-all peer-placeholder-shown:top-1/2 peer-placeholder-shown:text-sm peer-focus:top-3 peer-focus:text-xs"
            >
    Email
  </span>
        </label>
        
    </div>
</div>
</template>

<script>
export default {
    name: "Subscribe"
}
</script>

<style scoped>

</style>