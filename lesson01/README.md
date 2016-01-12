# 第一节 课程概要

AngularJS 是一个非常强大的JavaScript框架。他常被用在单页面应用(SPA)项目中。用添加属性的方式去扩展HTML DOM，并且更灵活的响应用户动作。AngularJS是一个开源框架并且完全免费，在全世界有着大量的开发者。

## 读者

本教程适合想要学习AngularJS基础和他的设计思维的专业前端程序员。简单易学，在描述的部门会配有响应的AngularJS例子。

## 需要具备的条件

你需要知道基础的JavaScipt知识和一些文本编辑工具。让我们开始开发基于AngularJS网络开发吧，如果你有了解HTML,CSS,AJAX相关知识会更有利与你学习本教程。

## Angular实例

下面是一个实例代码，请在编辑器上把下面的代码复制进去并运行他。

```
<!doctype html>
<html ng-app>
   
   <head>
      <script src = "../node_modules/angular/angular.js"></script>
   </head>
   
   <body>
      <div>
         <label>Name:</label>
         <input type = "text" ng-model = "yourName" placeholder = "Enter a name here">
         <hr />
         
         <h1>Hello {{yourName}}!</h1>
      </div>
      
   </body>
</html>

```