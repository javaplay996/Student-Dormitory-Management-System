﻿基于Vue.js和SpringBoot的学生宿舍管理系统是一个现代化的解决方案，旨在为高校提供一个高效、便捷的宿舍管理平台

项目录屏：https://www.bilibili.com/video/BV1ni4y1B7xp

### 1. 系统架构

#### 前端（Vue.js）

- **用户界面**：使用Vue.js框架构建，提供动态的用户交互和响应式设计。
- **组件化**：模块化设计，便于维护和扩展。

#### 后端（SpringBoot）

- **RESTful API**：提供与前端交互的数据接口。
- **数据库交互**：使用Spring Data JPA或MyBatis等技术与数据库进行交互。
- **安全性**：集成Spring Security进行用户认证和授权。

### 2. 角色和权限管理

- **管理员**：拥有系统的最高权限，可以管理所有模块和用户。
- **学生**：可以查看自己的宿舍信息、缴费记录、报修记录等。
- **宿管员**：负责日常的宿舍管理，如床位分配、卫生检查等。

### 3. 系统模块

#### 公寓资产管理

- **公寓信息管理**：录入、更新和删除公寓信息。
- **床位管理**：床位的分配、调整和状态更新。

#### 缴费信息管理

- **费用录入**：记录和管理学生的住宿费用。
- **缴费记录查询**：学生和管理员可以查看缴费历史。

#### 清理场所管理

- **清洁计划**：制定和调整清洁计划。
- **清洁记录**：记录每次清洁的执行情况。

#### 日常事务管理

- **报修管理**：学生可以提交报修请求，宿管员处理并记录。
- **通知发布**：管理员可以发布重要通知给所有用户。

#### 床位安排

- **床位分配**：根据学生需求和公寓情况自动或手动分配床位。
- **床位调整**：处理床位的调整请求。

### 4. 技术栈

- **前端**：Vue.js, Vuex, Vue Router, Element UI
- **后端**：Spring Boot, Spring Security, Spring Data JPA, Hibernate
- **数据库**：MySQL, PostgreSQL
- **服务器**：Nginx, Tomcat
- **版本控制**：Git

### 5. 安全性和性能

- **数据加密**：敏感数据如用户信息进行加密存储。
- **负载均衡**：使用Nginx进行负载均衡，提高系统性能。
- **缓存机制**：使用Redis等技术实现数据缓存，减少数据库访问压力。

### 6. 部署和维护

- **容器化**：使用Docker进行容器化部署，简化部署流程。
- **持续集成/持续部署**：集成CI/CD流程，自动化测试和部署。

这个系统的设计旨在提供一个全面、高效和用户友好的宿舍管理解决方案，通过角色划分和模块化设计，确保系统的灵活性和可扩展性。