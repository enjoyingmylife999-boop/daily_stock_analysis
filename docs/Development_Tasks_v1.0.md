# 🌍 Global Financial Cockpit

# 全球金融驾驶舱

---

## Development Tasks

## 开发任务

Version 1.0

Ashley.S

2026

---

# Table of Contents

# 目录

1. Task 001 — Inspect Current Workflow  
检查当前工作流

2. Task 002 — Redesign Feishu Report Template  
重设计飞书推送模板

3. Task 003 — Add Global Financial Cockpit Header and Footer  
添加全球金融驾驶舱开头与结尾

4. Task 004 — Add Market Snapshot  
添加市场概览

5. Task 005 — Add Why Chain  
添加为什么链

6. Task 006 — Add Financial Translator  
添加金融翻译器

7. Task 007 — Add Flight Log and Observation Checklist  
添加飞行日志与观察清单

8. Task 008 — Fix Schedule Timezone  
修复定时任务时区

9. Task 009 — Test and Review  
测试与检查

---

# Task 001

# Inspect Current Workflow

# 检查当前工作流

---

## Goal

Understand how the current project generates reports and sends Feishu notifications.

理解当前项目如何生成报告并发送飞书通知。

---

## Scope

Search the current report generation flow.

Search the Feishu notification sender.

Identify where the final message content is built.

---

## Requirement

Do not modify code in this task.

Only inspect and summarize.

---

## Acceptance Criteria

Codex should report:

• Main report generation file

• Feishu notification file

• Current message template location

• GitHub Actions workflow file

---

# Task 002

# Redesign Feishu Report Template

# 重设计飞书推送模板

---

## Goal

Replace the current report layout with Global Financial Cockpit style.

将当前报告样式替换为 Global Financial Cockpit 风格。

---

## Requirement

Do not change market analysis logic.

Only change user-facing message structure.

---

## Acceptance Criteria

The Feishu report should include:

• Global Financial Cockpit branding

• Compass AI identity

• Daily Flight title

• Flight Log

• Market report content

• Learning-oriented tone

---

# Task 003

# Add Global Financial Cockpit Header and Footer

# 添加全球金融驾驶舱开头与结尾

---

## Goal

Add fixed header and footer to every Feishu notification.

为每条飞书推送添加固定开头与结尾。

---

## Header Template

🌍 Global Financial Cockpit  
全球金融驾驶舱

Explore the world.  
Understand the market.  
Keep learning.

探索世界。  
理解市场。  
持续学习。

🧭 Compass AI

Navigation Online.

Today's mission is ready.

---

## Footer Template

🧭 Compass AI

Today's navigation completed.

See you tomorrow.

💡 Don't predict the market. Understand it.

💡 不要预测市场，而要理解市场。

---

## Acceptance Criteria

Every Feishu notification includes the header and footer.

---

# Task 004

# Add Market Snapshot

# 添加市场概览

---

## Goal

Add a short market overview section at the beginning of the report.

在报告开头增加简短市场概览。

---

## Requirement

The section should summarize the market in simple language.

It should be short and easy to read.

---

## Output

🌍 Market Snapshot  
市场概览

---

# Task 005

# Add Why Chain

# 添加为什么链

---

## Goal

Explain why important market events happened.

解释重要市场事件为什么发生。

---

## Requirement

Each Why Chain should answer:

• What happened?

• Why did it happen?

• Why does it matter?

• What should we observe next?

---

## Output

🧠 Why Chain  
为什么链

---

# Task 006

# Add Financial Translator

# 添加金融翻译器

---

## Goal

Translate professional financial concepts into understandable language.

将专业金融概念翻译成普通学习者能够理解的语言。

---

## Required Structure

Professional Term

专业术语

---

Simple Explanation

大白话解释

---

Analogy

生活比喻

---

# Task 007

# Add Flight Log and Observation Checklist

# 添加飞行日志与观察清单

---

## Goal

Add a learning summary and observation points to the report.

在报告中增加学习总结和观察方向。

---

## Output

📖 Flight Log  
飞行日志

---

✅ Observation Checklist  
观察清单

---

## Requirement

Observation Checklist should not provide investment advice.

It should only provide things to watch.

---

# Task 008

# Fix Schedule Timezone

# 修复定时任务时区

---

## Goal

Ensure scheduled tasks follow Asia/Shanghai time.

确保定时任务按照北京时间执行。

---

## Requirement

GitHub Actions cron uses UTC.

Convert Beijing time to UTC correctly.

---

## Target Timezone

Asia/Shanghai

UTC+8

---

# Task 009

# Test and Review

# 测试与检查

---

## Goal

Run GitHub Actions manually and verify Feishu notification.

手动运行 GitHub Actions 并检查飞书推送效果。

---

## Acceptance Criteria

• GitHub Actions succeeds

• Feishu receives the message

• Message format matches Global Financial Cockpit style

• No investment advice is generated

• Report remains readable on mobile
