# 前端面试要求我们一定要熟练掌握js！！！

## 2020/4/10 中移物联网笔试

- html链接中，src和href的区别

src表示引用资源，表示替换当前元素，用在img，script，iframe上，src是页面内容不可缺少的一部分（必须显示他页面才完整）<br/>
href标识超文本引用，用在link和a等元素上，href是引用和页面关联，是在当前元素和引用资源之间建立联系<br/>
[原网站戳我](https://blog.csdn.net/binlety/article/details/81448195)

- http请求的一种不包含那个？：get post trace fetch

八种请求：get，post，put， options，head，delete，trace，connect。<br/>
但是常用的就是get post，因为其他的请求都可以通过get post间接实现<br/>
[原网址戳我](https://www.cnblogs.com/baiqiantao/p/7672471.html)<br/>

- 谷歌浏览器的内核是什么？

webkit

- 常见浏览器的内核有哪些？

(1)Trident内核（微软ie）<br/>
(2)Gecko内核（火狐）<br/>
(3)WebKit内核（谷歌）<br/>
(4)Blink内核（谷歌和opera合办）这一渲染引擎是开源引擎WebKit中WebCore组件的一个分支，并且在Chrome（28及往后版本）、Opera（15及往后版本）中使用。<br/>

- 行内元素是什么？

元素分为行内元素和块状元素<br/>
行内元素只能在显示页面中的一行使用，不能横跨多行。比如：em – 强调，br – 换行，i – 斜体，img – 图片，input – 输入框<br/>
块状元素可以横跨多行。比如：form – 交互表单，h1 – 大标题，dir – 目录列表，div – 常用块级容易，也是css layout的主要标签<br/>
[原网址戳我](https://blog.csdn.net/web_ys/article/details/54629298)
- 那些元素可以嵌套

块元素可以包含内联（行内）元素或`某些`块元素（不是所有块元素都可以包含在另一个块元素内，比如div不能包含在p内）。<br/>
但内联（行内）元素却不能包含块元素，只能包含其他的内联元素。<br/>
[原网址戳我](https://blog.csdn.net/weixin_45761317/article/details/103103062)<br/>

- js中属于引用数据类型的有哪些？

js的六大数据类型：Number, String, Boolean, Undefined , Null , Object<br/>
基本数据类型：Number,String,Boolean,Undefined, Null。储存的是值，赋值之后相互之间不影响<br/>
引用数据类型：Object , Array, Function。储存的是引用，相互之间有影响。<br/><br/>

首先要明确ECMAScript中所有的函数的参数都是按值来传递的。<br/>
变量存储的基本类型的值只是把值传递给参数之后参数和这个变量互不影响。
变量存储的引用数据类型值存储的是该引用值在堆内存中的内存地址，因此传递的值就是这个内存地址。<br/>
[原文戳我](https://blog.csdn.net/sunday97/article/details/84869727)

- 添加css样式的方法有哪些？比如内联，外联。。

JSP页面插入CSS样式有三种方法，且其优先级不同。优先级：内联样式 > 内部样式 >外部样式！<br/>
【1】外部样式<br/>
在使用外部样式表的情况下，你可以通过改变一个文件来改变整个`站点`的外观。每个页面使用<link>标签链接到样式表。<br/>
`<link rel="stylesheet" type="text/css" href="<%=uiPath%>hwtt_ui/skins/<%=skinName%>/css/login.css" />`<br/>
rel 属性规定当前文档与被链接文档之间的关系，在该例子中rel 属性指示被链接的文档是一个样式表<br/>
type是当前元素本身的功能<br/>
href指定的是当前元素关联的文件的链接<br/><br/>

【2】内部样式<br/>
当单个`文档`需要特殊的样式时，就应该使用内部样式表。可以使用<style>标签在文档头部定义内部样式表。<br/>
  ```
   <style type="text/css">
        .loginBtn{
            display:block;
            cursor: pointer;
            height: 32px;
            margin-bottom: 1px;
            width: 100px;
        }
    </style>
  ```

【3】内联样式（inline style）<br/>
由于要将表现和内容混杂在一起，内联样式会损失掉样式表的许多优势。请慎用这种方法，例如当样式仅需要在`一个元素上应用一次`时。要使用内联样式，你需要在相关的标签内使用样式（style）属性。Style属性可以包含任何CSS属性。<br/>
`<input type="text" name="authCode" style="vertical-align: middle" />`<br/>
type是当前元素本身的功能<br/>
name是为了之后设置css样式时方便引用<br/>
style直接设置了css样式<br/><br/>

[原链接戳我](https://blog.csdn.net/J080624/article/details/69557267?depth_1-utm_source=distribute.pc_relevant.none-task-blog-OPENSEARCH-5&utm_source=distribute.pc_relevant.none-task-blog-OPENSEARCH-5)<br/><br/>

【4】如果插入的不是css而是js，则用<script> js们 <script/>在html中插入


## 和谁学，等一些公司的前端问题
- ul有序，ol无序吗？

- http的特点，他和https的区别

- 一个高为k的二叉树，他最多有2^k-1个节点吗？以及类似和二叉树深度，节点相关的公式类的题目

- 浏览器的两种储存方式

- 浏览器localStorage和sessionStorage区别

- git add是把文件保存到git的缓存区吗？
