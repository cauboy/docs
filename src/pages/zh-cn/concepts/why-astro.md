---
layout: ~/layouts/MainLayout.astro
title: 为什么是 Astro?
description: "Astro是集多功能于一体的Web框架，用于建立快速、以内容为中心的网站。了解更多。"
i18nReady: true
---

Astro 是**集多功能于一体的Web框架**，用于构建快速、以内容为中心的网站。

为什么选择 Astro 而不是其他的Web框架？以下的五个核心设计原则有助于解释我们为什么要构建 Astro，它需要解决的问题以及为什么 Astro 可能是您的项目或团队的最佳选择。

#### Astro是...
1. [ **以内容为中心** ](#以内容为中心)：Astro 专为内容丰富的网站而设计。
2. [ **服务器优先** ](#服务器优先)：网站在服务器上渲染 HTML 时运行速度更快。
3. [ **默认快速** ](#默认快速)：在 Astro 中构建缓慢的网站是不可能的。
4. [ **易于使用** ](#易于使用)：您不需要成为专家即可使用 Astro 构建某些内容。
5. [ **功能齐全且灵活** ](#功能齐全且灵活)：超100多种 Astro 集成可供选择。

## 以内容为中心
**Astro 皆为构建内容丰富的网站。** 这包括大多数营销网站、出版网站、文档网站、博客、个人作品集和一些电子商务网站。

相比之下，大多数现代 Web框架 都是为构建 Web应用程序 而设计的，这些框架最适合构建更复杂、类似应用程序的体验；管理仪表板、收件箱、社交网络、待办事项列表，甚至是像 [Figma](https://figma.com) 和 [Ping](https://ping.gg/) 这样的本地应用程序。

:::tip
如果您的项目属于第二个“应用”阵营，Astro可能不是您项目的正确选择...**没关系！**查看[Next.js](https://nextjs.org/)了解一个以应用程序为重点的绝佳Web框架替代方案。
:::




## 服务器优先
**Astro 尽可能利用服务器渲染而不是客户端渲染。** 这与传统服务器端框架（PHP、WordPress、Laravel、Ruby on Rails等）使用的方法相同，您不需要学习第二种服务端语言。 Astro 仍然使用 HTML、CSS和JavaScript(或TypeScript)。

这种方法与其他现代 JavaScript Web框架 形成鲜明对比，如 Next.JS、SvelteKit、Nuxt、Remix 等。这些框架需要整个网站的客户端和服务器端渲染，以解决性能问题，这种方法被称为**单页应用程序(SPA)，** 与 Astro 的**多页应用程序（MPA）** 方式形成鲜明对比。

SPA模式有它的优势。然而，这些都是以牺牲额外的复杂性和性能权衡为代价，这些权衡会损坏页面性能——包括[可交互时间(TTI)](https://web.dev/interactive/) 等关键指标——这对于以内容为中心的网站没有多大意义，因为这些网站的首次加载性能至关重要。

📚 [进一步了解 **Astro MPA** 架构的独特之处](/zh-cn/concepts/mpa-vs-spa/)




## 默认快速
良好的性能很重要，对于以内容为中心的网站尤其至关重要。事实证明，糟糕的表现会让您失去参与度、转化率和金钱。列如：
- 每快 100ms → 转化率增加 1% ([Mobify](https://web.dev/why-speed-matters/), 收入 +$380,000/年)
- 每快 50% → 销售额增加 12% ([AutoAnything](https://www.digitalcommerce360.com/2010/08/19/web-accelerator-revs-conversion-and-sales-autoanything/))
- 每快 20% → 转换率增加 10% ([Furniture Village](https://www.thinkwithgoogle.com/intl/en-gb/marketing-strategies/app-and-mobile/furniture-village-and-greenlight-slash-page-load-times-boosting-user-experience/))
- 每快 40% → 注册率增加 15% ([Pinterest](https://medium.com/pinterest-engineering/driving-user-growth-with-performance-improvements-cfc50dafadd7))
- 转换速度提高 850ms → 转化率增加 7% ([COOK](https://web.dev/why-speed-matters/))
- 每慢1秒 → 减少 10% 的用户 ([BBC](https://www.creativebloq.com/features/how-the-bbc-builds-websites-that-scale))

在许多 Web框架 中，在开发过程中很容易构建一个看起来很棒的网站，但是在部署后加载速度会非常慢。JavaScript 通常是罪魁祸首，因为用户的手机和低功耗设备很少能与开发人员的电脑速度相匹配。

Astro 的魔力在于它如何将上述两个值（内容焦点于服务器优先的MPA架构）相结合，以做出权衡并提供其他框架无法实现的功能。结果是每个网站都有开箱即用令人惊叹的Web性能。我们的目标：**使用 Astro 构建几乎不可能缓慢的网站。**

与使用最受欢迎的 React Web框架 构建相同的网站进行比较，Astro 网站的[加载速度快40%，JavaScript减少90%](https://twitter.com/t3dotgg/status/1437195415439360003) 。请对我们的结论半信半疑：观看 Astro 的现场直播 让 Ryan Carniato(Solid.js和Marko的创造者) [无言以对](https://youtu.be/2ZEMb_H-LYE?t=8163).



## 易于使用
**Astro的目标是让每位Web开发人员都可以访问。** Astro 被设计成熟悉和平易近人的感觉，无论技能水平或过去的Web开发经验如何。

我们首先确保您可以使用您已经知道的任何喜欢的 UI 组件语言。在 Astro 中创建新的 UI 组件时都支持React、Preact、Svelte、Vue、Solid、Lit 和其他一些组件。

我们为了 Astro 也能有一个很好的内置组件语言，我们创建了自己 `.astro` UI语言。它很大程度上深受 HTML 的影响：任何有效的 HTML 部分都已经是有效的 Astro组件，它还结合了我们从其他组件中借用的一些功能，如：React的JSX表达式和 CSS范围（默认为Svelte和Vue）。

Astro 的设计比其他UI框架和语言更简单，其中一个重要原因是 Astro 被设计为在服务器上渲染而不是浏览器，这意味着您无需担心：React Hooks、stale closures(React)、refs(Vue)、observables(Svelte)、atoms、selectors、reactions or derivations。服务器上没有反应，因此这些复杂性都消失了。

我们最喜欢的谚语之一是：**选择加入复杂性。** 我们设计 Astro 是为了尽可能多地从开发人员体验中消除“所需的复杂性”，尤其是您首次加入时。您可以在 Astro中使用 HTML和CSS构建“Hello World”示例网站。然后当您需要构建更强大的功能时，您可以随时获得新功能和API。




## 功能齐全且灵活

**Astro 是集多功能于一体的Web框架，提供了构建网站所需的一切** Astro 包括组件语法、基于文件的路由、资产处理、构建处理、捆绑、优化、数据获取等。您可以在不超过 Astro核心功能集 的情况下构建出色的网站。

如果您需要更多的控制，你可以通过 [React](https://www.npmjs.com/package/@astrojs/react), [Svelte](https://www.npmjs.com/package/@astrojs/svelte), [Vue](https://www.npmjs.com/package/@astrojs/vue), [Tailwind CSS](https://www.npmjs.com/package/@astrojs/tailwind), [MDX](https://www.npmjs.com/package/@astrojs/mdx), [image optimizations](https://www.npmjs.com/package/@astrojs/images)等[100多个集成](https://astro.build/integrations/) 扩展 Astro 只需要一个命令 [即可连接您喜欢的CMS](https://astro.build/integrations/) 或 [部署到您喜欢的服务器](/zh-cn/guides/deploy/)

Astro 与 UI 无关，这意味着您可以自带UI框架（BYOF）。React、Preact、Solid 、Svelte、Vue和 Lit都在Astro中得到官方支持。您甚至可以在同一页面上混合和匹配不同的框架，使未来的迁移更容易，并防止项目锁定到单个框架。

<!-- 在Astro中使用你最喜欢的UI框架，或者在不同的页面、网站、甚至团队中混合和匹配UI组件。你甚至可以在每个单独的页面上逐个选择你的UI框架组件，以获得最大的灵活性和最小的承诺。Astro还为你提供了一张 "摆脱（框架）牢狱之灾 "的卡片，让你可以逐步转换你的整个项目，而不中断你的网站。 -->

<!-- 这对大型企业来说有一个额外的好处：你可以在不增加服务器端代码的复杂性的情况下增加公司支持的UI框架的数量。每个Astro网站都有相同的服务器运行代码，无论你使用哪种UI框架。这大大降低了生产的复杂性，而不是运行用Next.js、SvelteKit和Nuxt构建的不同网站。 -->

<!-- 📚 转至: 链接到多框架支持？  -->

<!-- ## 默认快速 -->

<!-- 如上所述，Astro 构建了快速的网站。但我们对性能的关注不仅仅是Astro的“可能性”。我们希望良好的性能成为自动默认值。   -->

<!-- 当我们构建Astro时，我们厌倦了Web框架，这些框架*可以*在正确的人手中快速完成，但对于不了解每个选项或最佳实践的普通用户来说，这感觉很慢。我们有一个疯狂的想法：你甚至不应该考虑性能来构建一个快速的网站。我们的目标很简单：**使用Astro构建一个缓慢的网站应该非常困难。** -->

<!-- 这种默认快速的想法激发了许多其他Astro设计选择和默认行为，除了上面提到的部分水合作用。默认情况下，您的 JavaScript 和 CSS 是捆绑在一起的。默认情况下，您部署的服务器支持流式 HTML。第三件事当你使用Astro进行构建时，你会看到这些设计决策如何塑造你“在Astro中”的工作方式  -->

<!-- (// 我对最后一行的想法是：既定目标是让读者思考Astro中的事情是如何运作的。有了这样的小推，读者就更准备好了，这是如何工作的，我可能不得不调整我的期望。 //) -->


