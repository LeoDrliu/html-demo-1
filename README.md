# HTML入门笔记一

1. HTML的发明者是李爵士

2. HTML的起手式

   ```html
   <!-- 文档类型 -->
   <!DOCTYPE html>
   
   <!-- html标签，lang属性标识语言 -->
   <html lang="zh-CN">
   
   <!-- head，看不见的东西 -->
   
   <head>
       <!-- 字符编码 -->
       <meta charset="UTF-8">
       <!-- 使用最新内核 -->
       <meta http-equiv="X-UA-Compatible" content="IE=edge">
       <!-- 禁用缩放 -->
       <meta name="viewport" content="width=device-width, initial-scale=1.0">
       <!-- html文档标题 -->
       <title>Document</title>
   </head>
   
   <body>
   
   </body>
   
   </html>
   ```

3. 常用章节标签

   - 标题`<h1>、<h2>...`
   - 章节`<section>`
   - 文章`<article>`
   - 段落`<p>`
   - 头部`<header>`（如广告）和尾部`<footer>`（如版权）
   - 主要内容`<main>`和没啥用的旁支内容`<aside>`
   - 划分`<div>`

4. 全局属性

   - `clas` 标签类别
   - `contenteditable`标签内容可编辑
   - `hidden`隐藏标签，优先级高于display:none
   - `id`表示全页面唯一的标签，类似于class，但尽量不用id
   - `style` 作用类似于`<style>`，优先级高于样式标签内的css，低于js中的样式
   - `tabindex`用于tab键选中标签，正值为tab键的顺序，0为最后，-1为不可访问
   - `title`鼠标显示的浮现文本

5. 常见内容标签

   ```html
           <!-- ordered list -->
           <ol>
               <li>item1</li>
               <li>item2</li>
           </ol>
   
           <!-- unordered list -->
           <ul>
               <li>a</li>
               <li>b</li>
           </ul>
   
           <dl>
               description list
               <dt>description term</dt>
               <dd>description data</dd>
           </dl>
   
           <pre>保留空格，标签内容全部展示</pre>
   
           <code>代码</code>
   
           <!-- 分隔线 -->
           <hr>
   
           <!-- break -->
           <br>
   
           <!-- 斜体 -->
           <em></em>
   
           <!-- 加粗 -->
           <strong></strong>
   
           <!-- 块级引用 -->
           <blockquote>安得广厦千万间，大庇天下寒士俱欢颜</blockquote>
   ```

