# ~/vc2333

This repository is the repository of my homepage (unspecified) that can be used as a template.

Visit unspecified for a live deployment of the `master` branch.

Text contents are mainly located in `index.html`. Simply edit this file to replace the texts and the picture.

For further modifications, including color settings, background images, and layouts, check `index.css` and `stylesheets/*.css`. Don't forget to run an `npm run build` to rebuild files and reflect your modification.

---

这里是 unspecified 的代码库，也可以用来作为制作页面的模版。

访问 unspecified 可以查看 `master` 分支的最新部署。

大部分的文本内容储存在 `index.html` 中，修改这个文件即可更改页面的主图片和文本。

若要进行更进一步的修改（如配色方案、背景图片与页面布局），请编辑 `index.css` 与 `stylesheets/*.css`。完事了别忘记 `npm run build` 一下来重新编译使更改生效。

## warning

You should replace these assets with your images, all of them, before deploying to your websites.

---

你应该在部署到你的网站或分发之前，将这些所有的版权图片替换为你自己的图片。

## build

To build this project, run these following commands.

```
npm install . 
npm run build
```

You may check your `NODE_ENV` before executing `npm install .` to ensure `devDependencies` are installed.

---

运行下面的指令即可完成编译这个仓库。

```
npm install .
npm run build
```

运行 `npm install .` 前，你也许应该检查一下 `NODE_ENV` 来确保 `devDependencies` 被正确安装。

## known "issue"

The chemical symbol in the name may flash on page load, especially on Chrome.  
This is a bug specific to Chrome (and Blink browsers). However, this won't be fixed, because it's caused by Chrome and left not fixed for years.  
Check out this issue for a solution if this bothers you. (Thanks to @Nyaasu66)

https://github.com/amphineko/amphineko/issues/15

---

使用 Chrome 时，页面上部名字中的化学符号可能会闪烁。  
这是一个 Chrome (和使用了 Blink 的浏览器) 特有的 Bug。因为这是由 Chrome 产生并且多年没有修复的问题，所以在这里也不会修复。  
如果这给你产生了困扰，以下 issue 提供了一个解决方法。(感谢 @Nyaasu66)

https://github.com/amphineko/amphineko/issues/15
