# 通讯录项目 - 后端
技术栈：Node.js + Express + MySQL
功能：提供联系人增删改查接口

## 本地启动步骤
1. 安装依赖：npm install
2. 配置数据库：修改 src/db.js 中的MySQL密码
3. 启动服务：node src/app.js
4. 接口地址：http://localhost:3001/api/contacts

## 接口说明
- GET /api/contacts：获取所有联系人
- POST /api/contacts：添加联系人（参数：name, phone）
- PUT /api/contacts：修改联系人（参数：id, name, phone）
- DELETE /api/contacts/:id：删除联系人（路径参数：id）