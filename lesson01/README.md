# 第一节 课程概要

AngularJS 是一个非常强大的JavaScript框架。他常被用在单页面应用(SPA)项目中。用添加属性的方式去扩展HTML DOM，并且更灵活的响应用户动作。AngularJS是一个开源框架并且完全免费，在全世界有着大量的开发者。

## 读者

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