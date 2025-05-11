# 智学智联门户说明书
---
## 🧾 项目介绍
---
**本项目基于 Django 框架精心打造，集三大核心功能模块于一体，旨在为教育管理及服务型企业门户开发提供强大助力。其功能模块设计全面且实用，无论是教育资源的高效整合、人员信息的精细管理，还是服务项目的在线展示与交互，都能轻松应对，助力企业与教育机构在数字化运营中脱颖而出，实现业务流程的高效化与智能化转型。
**

---
## ✨ 功能模块介绍
---
### 1.课程学生管理 (coursestudent)

---
### 2. 访客服务 (guestapp)

---
### 3. 家长门户 (parentsapp)

---
<!-- by 吴和师 -->
### 📦 环境要求

- - Python 3.8+
- Django 3.2+
- SQLite 3.0+
------

🛠️ 安装步骤
1. 克隆仓库
git clone https://github.com/Lcz-lczg/django-project-11AM.git
cd django-project-11AM
2. 配置虚拟环境
# 创建虚拟环境
python -m venv venv

# 激活环境

.\venv\Scripts\activate


source venv/bin/activate
3. 安装依赖
pip install -r requirements.txt
注意：若路径不同请指定完整路径

4. 数据库迁移
python manage.py makemigrations
python manage.py migrate
5. 创建管理员
python manage.py createsuperuser
6. 运行项目
python manage.py runserver
📁 项目结构
django-project-11AM-main/
├── coursestudent/    # 课程管理
├── guestapp/         # 访客功能
├── parentsapp/       # 主门户系统
│   ├── static/       # 静态资源
│   └── templates/    # 网页模板
└── manage.py         # 管理脚本
    
🚀 使用提示
访问 管理后台 使用创建的管理员账号登录
按 Ctrl+C 停止开发服务器
生产环境建议使用 Nginx + Gunicorn 部署
<!-- by 吴和师 -->


