---
sidebar: auto
---

# 常见问题

## `@vuepress/plugin-blog` 和 `@vuepress/theme-blog` 有什么区别?

VuePress 的默认主题侧重于文档站点，因此提供适当的博客支持应当在另一个单独的主题中。

我们希望为开发人员提供默认的博客主题，并且鼓励社区主题的开发。该插件系统是在 VuePress 1.x 发布时引入的。其目的是去耦和可重用。因此，我们尝试在插件中实现所有常见和必要的博客功能，并更加关注主题中的交互体验。

使用博客主题，你可以在几分钟之内完成博客设置，并专注于内容。使用博客插件，你可以通过专注于用户界面来开发自己的主题，而无需了解幕后逻辑。

> 这是不可见的，用户不感兴趣。

## 为什么此插件中有几个插件?

这是一个多合一的插件，所有通用和必要的功能都在一个插件中实现。我们不希望你花费大量时间寻找可用的插件，也不想重新造轮子。

你只需要安装此插件，而不用安装 `yarn add -D @vuepress/plugin-blog vuepress-plugin-sitemap vuepress-plugin-mailchimp vuepress-plugin-disqus` 之类的插件。当然，你可能不需要某些插件。不用担心，如果你不启用它们，它们将永远不会被使用。

此外，我们将一些功能提取到插件中，因为它们不仅可以被博客使用，还可以有其他用途。
