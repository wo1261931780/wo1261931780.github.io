<!--
 * @Author: junw 45444154+wo1261931780@users.noreply.github.com
 * @Date: 2023-03-24 21:21:55
 * @LastEditors: junw 45444154+wo1261931780@users.noreply.github.com
 * @LastEditTime: 2023-03-24 21:30:00
 * @FilePath: \wo1261931780.github.io\README.md
 * @Description: 1111
 *
 * Copyright (c) 2023 by ${git_name_email}, All Rights Reserved.
-->

***我是博客readme***

## 项目架构

```mermaid
graph TB
    subgraph 博客系统["博客系统"]
        A[GitHub Pages] --> B[静态网站托管]
        B --> C[个人博客展示]
        C --> D[技术文章分享]
    end
    
    subgraph 内容模块["内容模块"]
        E[Markdown文档] --> F[HTML渲染]
        F --> G[样式主题]
        G --> H[响应式布局]
    end
    
    subgraph 部署流程["部署流程"]
        I[本地编写] --> J[Git提交]
        J --> K[GitHub Actions]
        K --> L[自动部署]
        L --> M[在线访问]
    end
    
    博客系统 --> 内容模块
    内容模块 --> 部署流程
    
    style A fill:#4A90E2,stroke:#2E5C8A,color:#fff
    style B fill:#5BA3F5,stroke:#2E5C8A,color:#fff
    style C fill:#6BB5F7,stroke:#2E5C8A,color:#fff
    style D fill:#7BC7FA,stroke:#2E5C8A,color:#fff
    style E fill:#50C878,stroke:#2E7D4D,color:#fff
    style F fill:#60D488,stroke:#2E7D4D,color:#fff
    style G fill:#70E098,stroke:#2E7D4D,color:#fff
    style H fill:#80ECA8,stroke:#2E7D4D,color:#fff
    style I fill:#FFB84D,stroke:#CC8F3D,color:#fff
    style J fill:#FFC570,stroke:#CC8F3D,color:#fff
    style K fill:#FFD293,stroke:#CC8F3D,color:#fff
    style L fill:#FFDFB6,stroke:#CC8F3D,color:#fff
    style M fill:#FFECD9,stroke:#CC8F3D,color:#333
```
