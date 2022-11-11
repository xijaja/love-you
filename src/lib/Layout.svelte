<script lang="ts">
  export let say: string = "Heart";
</script>

<div class="h-screen dark:bg-gray-900">
  <div class="px-6 mx-auto max-w-screen-lg">
    <h1 class="py-4 font-mono text-pink-400 dark:text-white">
      {"❤️ " + say + " ❤️"}
    </h1>
    <hr class="py-4 border-pink-100 dark:border-gray-500" />
    <!-- 这里是子组件 -->
    <slot />
  </div>
</div>
