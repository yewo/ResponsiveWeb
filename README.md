# 响应式开发

### 1. 概念

让不同设备的屏幕更好的适应与浏览网站，以完美适配任何尺寸的屏幕，网站只需要一个版本就能浏览全部内容

![响应式网站的优点](https://raw.githubusercontent.com/yewo/ResponsiveWeb/master/doc/img/响应式网站的优点.png)

![响应式网站的缺点](https://raw.githubusercontent.com/yewo/ResponsiveWeb/master/doc/img/响应式网站的缺点.png)



### 2. viewport视口

- width: 视口宽度
- device-width：设备屏幕的宽度

   **让布局视口成为理想视口**

![viewport视口](https://raw.githubusercontent.com/yewo/ResponsiveWeb/master/doc/img/viewport视口.png)



### 3. 职责

以下工作任务都不需要前端工程师来做，我们的事情就是根据需求和设计图，来实现页面的效果

![网站开放前的工作](https://raw.githubusercontent.com/yewo/ResponsiveWeb/master/doc/img/网站开放前的工作.png)



### 4. 分析设计图

![怎样分析设计图](https://raw.githubusercontent.com/yewo/ResponsiveWeb/master/doc/img/怎样分析设计图.png)

以下为最终效果图

![响应式网站](https://raw.githubusercontent.com/yewo/ResponsiveWeb/master/doc/img/响应式网站.png)



### 5. 实践原则

- 渐进增强
- **优雅降级**

####   屏幕的选择

​	移动端与PC端两者之间，根据用户量来确定

####   浏览器的选择

![浏览器](https://raw.githubusercontent.com/yewo/ResponsiveWeb/master/doc/img/浏览器.png)

![Chrome](https://raw.githubusercontent.com/yewo/ResponsiveWeb/master/doc/img/Chrome.png)

#### 断点的选择

​	即媒体查询中的临界点

​	不要去针对特定的设备去选择，而是针对屏幕的大小来分割.  如下图

![响应式断点选择](https://raw.githubusercontent.com/yewo/ResponsiveWeb/master/doc/img/响应式断点选择.png)



