

# 1 Offical Requirements

Es ist auch erlaubt, die Webanwendung in ein JS-Frontend (z.B. mit Reactjs, Vuejs) und ein PHP-Backend aufzuteilen. An die Anwendung gesendeten Daten müssen dennoch immer auch serverseitig validiert werden.

Instead of a written exam, this course requires a **project**: each student must create their own **PHP web application**.  
The use of a framework is recommended but **not mandatory**.  
You are free to choose the purpose of your web application.

## 1.1 Basic Requirements

- The web application must use a **database**.
    
- The data model of the application must contain at least **three entities** in addition to users (e.g., categories, products, orders).
    
- The application must have at least **two user groups** (e.g., “customers” and “end users”).
    
- At least one user group (e.g., “customers”) must be able to **register and log in** to use the functions intended for them.
    
- The application must **not send any emails**.
    
- All user groups must have the ability to **input data** (not just read-only access).
    
- You must integrate a **payment service provider** (e.g., Stripe or Paddle) so that at least one user group can subscribe to your application for a fee.
    
    - It is sufficient to provide a single subscription option (e.g., €2 per month).
        
    - _Note: Payment providers offer a test mode or sandbox environment for testing._
        
- You may use **plugins or packages**, but you must explicitly declare them.
    
    - These must not be paid, at least not for students.
        
- You must clearly indicate which parts of the code you wrote yourself and which parts come from external sources.
    

## 1.2 Examples of Web Applications

_(Note: “manage” here can mean create, read, update, and/or delete.)_

### 1.2.1 Very Simple Online Shop Platform

- **Customers (logged in):**
    
    - Manage online shops
        
    - Manage categories
        
    - Manage products (including photo upload)
        
    - Manage orders
        
- **End users (not logged in):**
    
    - Visit online shop
        
    - Select products
        
    - Enter orders
        

### 1.2.2 Very Simple Podcast Platform _(or photo platform, or blog platform, etc.)_

- **Customers (logged in):**
    
    - Manage podcasts (including photo upload)
        
    - Manage podcast episodes (including uploading MP3 files)
        
- **End users (not logged in):**
    
    - Visit podcast website
        
    - Listen to audio files (web player)
        
    - Enter comments
        

### 1.2.3 Very Simple Survey Platform

- **Customers (logged in):**
    
    - Manage questionnaires
        
    - Manage questions
        
    - Manage answers
        
- **End users (not logged in):**
    
    - Read questions
        
    - Enter answers
        

## 1.3 Submission Requirements

- **Source code** of the web application:
    
    - Cleanly structured
        
    - Clear distinction between own and external code
        
- **Link to a video** (5–10 minutes) in which you:
    
    - Present your web application
        
    - Explain your source code



# 2 中文版 

## 2.1 基本要求

- 网络应用必须使用 **数据库**。
- 应用的数据模型除了用户外，至少包含 **三个实体**（例如：类别、产品、订单）。
- 应用必须至少有 **两类用户组**（例如：“客户”和“终端用户”）。
- 至少一类用户组（例如：“客户”）必须能够 **注册和登录**，以便使用为他们提供的功能。
    
- 应用必须 **不能发送任何电子邮件**。
    
- 所有用户组都必须具备 **数据输入功能**（≠ 仅有只读访问）。
    
- 必须集成一个 **支付服务提供商**（如 Stripe 或 Paddle），以便至少有一类用户组能够通过付费订阅方式访问应用。
    
    - 只需提供一个可订阅的套餐即可（例如：每月 2 欧元）。
        
    - _提示：支付服务商一般提供测试模式或沙盒环境。_
        
- 可以使用 **插件或第三方包**，但必须明确说明。
    
    - 插件/包不得收费，至少对学生必须免费。
        
- 必须清晰标注哪些代码是外部来源，哪些是自己编写的。

## 2.2 满足要求的应用示例

> 注：“管理”在这里可以指 **创建、读取、修改和/或删除**。

### 2.2.1 简单的在线商店平台

- **客户（已登录）：**
    
    - 管理网店
        
    - 管理类别
        
    - 管理产品（包括照片上传）
        
    - 管理订单
        
- **终端用户（未登录）：**
    
    - 浏览网店
        
    - 选择产品
        
    - 输入订单
        

### 2.2.2 简单的播客平台 _(或照片平台、博客平台等)_

- **客户（已登录）：**
    
    - 管理播客（包括照片上传）
        
    - 管理播客集数（包括上传 MP3 文件）
        
- **终端用户（未登录）：**
    
    - 浏览播客网站
        
    - 收听音频文件（网页播放器）
        
    - 输入评论
        

### 2.2.3 简单的问卷调查平台

- **客户（已登录）：**
    
    - 管理问卷
        
    - 管理问题
        
    - 管理回答
        
- **终端用户（未登录）：**
    
    - 阅读问题
        
    - 输入回答
        

## 2.3 提交要求

- **网络应用源代码**
    
    - 结构清晰
        
    - 明确区分自编代码与外部代码
        
- **一个视频链接**（5–10 分钟）：
    
    - 展示您的网络应用
        
    - 讲解您的源代码


# 3 我觉得还可以的项目 

中文的
- https://github.com/jcc/blog
- https://github.com/baijunyao/laravel-bjyblog?tab=readme-ov-file


外文
- https://github.com/binshops/laravel-blog
- https://github.com/larajournal/larajournal 
- https://github.com/alimranahmed/LaraBlog?tab=readme-ov-file  没有新用户 register 系统 

视频 
- 外文 
    - https://www.youtube.com/watch?v=Njwbbfw_Qm0&list=PLqDySLfPKRn5cEn5H2djYJNcmlaYWz-L3&index=3
        - https://github.com/yelocode/tailwind-css-blog/blob/main/post.html
    - https://www.youtube.com/watch?v=qC1OV7P7wPE&list=PLSJxovi1IyDEXjModUFzeu1nxje5-aiCA&index=2  免费 这个好但没有解说
        - 源码 https://drive.google.com/file/d/19pBzzdXgy9nJ3O71KyHsmmcp4jqjGRfV/view
- 中文
    -  https://www.bilibili.com/cheese/play/ep722158?query_from=0&search_id=18332427871802246773&search_query=php+laraval+%E5%8D%9A%E5%AE%A2&csource=common_hpsearch_null_null&spm_id_from=333.337.search-card.all.click 
        - 68 元购买 
    - https://www.bilibili.com/video/BV185411x7so?spm_id_from=333.788.videopod.episodes&vd_source=55e5cc2f534c16c73bbeb684e98c4195&p=14 太老了 

Integrating Stripe with PHP
- https://www.youtube.com/watch?v=v3umP14nCYU 
- https://www.youtube.com/watch?v=EildM6OMcoQ   + https://www.youtube.com/watch?v=3aef3fs2CpQ
    - **https://github.com/bradtraversy/php_stripe_paypage**