<script lang="ts">
  // 导出初始数据，允许外部组件访问
  export let count: number = 0;

  // 用于存储计数器的值
  const increment = () => {
    count += count;
  };
</script>

<section>
  <p class="dark:text-gray-100">现在的数字是：{count}</p>
  <button
    class="border px-6 py-2 mt-3 rounded-lg bg-gradient-to-br from-green-300 to-blue-400 text-white select-none dark:border-none"
    on:click={increment}
  >
    点击翻倍
  </button>
</section>
