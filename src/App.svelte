<script lang="ts">
  // 导入路由包
  import { Router } from "svelte-spa-history-router";
  // 导入页面路由
  import Home from "./pages/Home.svelte";
  import Heart from "./pages/Heart.svelte";

  // 路由配置
  const routes = [
    // 首页
    { path: "/", component: Home },
    // Heart 页
    { path: "/heart", component: Heart },
  ];
</script>

<!-- 路由 -->
<Router {routes} />
