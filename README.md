# jsStudy 
## 开始学习react
### 组件

    创建组件：var HelloMsg = React.createClass();
    使用组件：<HelloMsg/>

    注意事项：
    - ①必须指定render方法
    - ②组件名称首字母必须是大写的
    - ③在组件中如果要返回多个元素，必须放在一个容器中。

    JSX语法让React组件：支持自定义元素和组件，结合运算或者表达式添加数据，让组件变得更强大。

    将多个组件 ，整合在一起，就可以构造更复杂的页面展示效果，一般称之为复合组件。
    1、认识react，认识react的核心概念和核心特性、环境搭建、
    2、第一个react页面，学习jsx语法，js表达式的执行情况 组件的基本使用
    3、复合组件 （练习实现登录窗口）
    4、复合组件之父子通讯props（练习，通过props指定登录窗口各文本信息）
    5、this.props.children 与组件之间通讯refs
### 组件间的通信
