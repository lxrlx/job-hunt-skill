# 发布指南 · job-hunt-advisor（通用求职面试助手）

本目录是一个**已去除所有个人隐私**的通用 WorkBuddy 技能，可直接公开发布。两种发布方式如下。

## 一、发布到 GitHub 公开仓库（最推荐，约 2 分钟）

### 第 1 步：在 GitHub 上建仓库
- 打开 https://github.com/new
- Repository name 填：`job-hunt-skill`
- 选 **Public**
- **不要**勾选 "Add a README file"（本地已有）
- 点 Create repository

### 第 2 步：推送（本机已配 Git Credential Manager，会自动用你缓存的 GitHub 凭据）
在本目录执行：
```bash
git remote add origin https://github.com/lxrlx/job-hunt-skill.git
git branch -M main
git push -u origin main
```
> 若弹出登录，用浏览器完成 GitHub 授权即可。

### 第 3 步：验证
打开 https://github.com/lxrlx/job-hunt-skill ，应看到 `README.md`、`LICENSE`、`job-hunt-advisor/` 三项内容。

## 二、上架 WorkBuddy 技能市场
1. 将 `job-hunt-advisor/` 文件夹（或本目录的 `job-hunt-advisor.zip`）作为技能包提交到 WorkBuddy 技能市场审核。
2. 审核通过后，其他用户在 WorkBuddy 内搜索「求职面试助手 / job-hunt-advisor」即可一键安装。
3. 提交入口以 WorkBuddy 当前版本为准：左侧「专家 / 技能」相关入口 → 发布技能。

## 三、别人怎么用
克隆或安装后，把 `job-hunt-advisor/references/profile.md` 里的 `{{占位符}}` 换成自己的真实信息，然后在对话里提「简历 / JD / 面试 / 模拟面试 / BOSS 打招呼 / 求职计划 / 匹配度 / 反问」等词即可触发。

## 四、你的私人版不受影响
你本地 `~/.workbuddy-ai/skills/job-hunt/`（刘笑冉个人定制版）保持不动、不公开；本仓库是全新的通用版，二者互不干扰。
