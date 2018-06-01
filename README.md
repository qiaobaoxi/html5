# html5

## html <!DOCTYPE html> 标签
    
### 定义和用法
    
      <!DOCTYPE html>声明必须时html文档的第一行，位于<html标签之前>
    
### 不是html标签
    
      指示web浏览器关于页面使用那个html版本进行编写的指令
      
## 文档类型定义

### DTD
    
    DTD可定义合法的XML文档构建模块，它使用一系列合法的元素来定义文档的结构

### 在html中
    
    DTD规定了标记语言的规则，这样浏览器才能正确的呈现内容

### html5
    
    html5不是基于SGML,所以不需要引用DTD
    
## 新增标签

### 结构标签

    结构标签（块状元素）-有意义的div
      
      <artical> 标记定义一篇文章
      
      <header>  标记定义一个页面或一个区域的头部
      
      <nav> 标记定义导航链接
      
      <section> 标记定义一个区域
      
      <aside> 标记定义页面内容部分的侧边栏
      
      <hgroup> 标记定义文件中一个区块的相关信息
      
      <figure> 标记定义一组媒体内容以及他们的标题
      
      <figcaption> 标签定义figure元素的标题
      
      <footer> 标记定义一个页面或一个区域的地步
      
      <dialog> 标记定义一个对话框（会话框）类型微信
 
## 多媒体标签

### 三类多媒体标签
    
    <video> 标记定义一个视频
   
    <audio> 标记定义音频内容
    
    <source> 标记定义媒体资源
    
    <canvas> 标记定义画布
    
    <embed> 标记定义外部的可交互的内容或插件，比如flash
    
    标签意义：多媒体标签的出现意味着富媒体的发展以及支持不使用插件的情况下即可操作媒体文件，极大的替身了用户体验
    
## web应用标签

### 状态标签

    <meter> 状态标签（实时状态显示：气压、气温）
    
    <progress> 状态标签（任务过程：安装、加载）
    
### 列表标签
     
    <datalist> 为input标记定义一个下拉列表，配合option
    
    <details>  标记定义一个元素的详细内容，配合summary

### 其他标签

     注释标签
     
     <ruby>  标记定义注释或音标
     
     <rt>    标记定义对ruby的注释内容文本
     
     <rp>    告诉那些不支持ruby元素的浏览器如何去显示
     
     <make> 标记定义有标记的文本（黄色选中状态）
     
     <output> 标记定义一些输出类型，计算表单结果配合oninput事件
