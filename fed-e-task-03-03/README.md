问题：SSR中用户输入一个路径（比如网站首页，这儿我暂叫做 index 模块），此时服务端只执行 index 模块的 DOM 的渲染，其它的路由下的模块不渲染，并把渲染了 index 模块和没有渲染的模块（交给客户端渲染）的包返回给客户端。然后客户端在访问其它 hash（index 模块之外的 hash）的时候在加载其它模块的 js 和渲染（正常的单页应用的流程）




