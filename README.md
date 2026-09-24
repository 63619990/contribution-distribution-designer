# 贡献计量与分配设计器（Web3 防骗工具箱）

> 本技能由《价值互联网产业应用蓝皮书（2025）》经 cangjie-distill 蒸馏流水线提取编排，帮助普通用户识别真假 Web3、厘清合规边界、避开资金盘陷阱。

## 功能简介
当用户需要把多元要素贡献可信计量并公平分润、替代"资本主导、主观裁定"分配时使用——
  典型信号："怎么让多方按贡献公平分钱/分润""不想让平台抽成""怎么设计通证/积分分配规则"
  "怎么把用户贡献计量出来并自动发奖励""贡献即确权怎么落地成代码"。
  适用：社区/平台设计者构建可代码化的经济模型（确权→计量→分配→可追溯）。
  不适用：单纯做概念辨析或合规定性（用 S1 概念辨析器）；只问"怎么搭社区、怎么活跃用户"
  （用 S6 共建社区）；面向境内零售发行代币化融资（须先触发 S2 合规红线检查）。

## 来源与署名
- **来源**：《价值互联网产业应用蓝皮书（2025）》（"价值互联网产业应用蓝皮书"编写组，主编：梁超杰）。
- **署名**：蓝皮书原著著作权归编写组及相关作者；本技能改写与编排归贡献者。
- **开源协议**：**Apache-2.0**（仅覆盖本技能改写与编排，不覆盖蓝皮书原著）。引用蓝皮书原文须注明出处。

## 安装方式

### 方式一：从 ClawHub 一键安装（推荐）
在 ClawHub 搜索 `contribution-distribution-designer`，或用 CLI：
```bash
clawhub skill install contribution-distribution-designer
```

### 方式二：从 GitHub 安装
```bash
git clone https://github.com/63619990/contribution-distribution-designer.git
cp -r contribution-distribution-designer/ ~/.workbuddy/skills/
```
重启 WorkBuddy 后，对话出现相关信号即自动激活。

### 方式三：手动安装
将本仓库 `contribution-distribution-designer/` 目录整体复制到 `~/.workbuddy/skills/`（Windows 为 `%USERPROFILE%\.workbuddy\skills\`）。

## 合规声明
本技能提炼自蓝皮书第三篇·第五章「合规边界」，仅供风险识别与科普参考，**不构成任何投资建议、法律意见或投资邀约**。中国境内不得涉及通证代币化等加密金融行为；虚拟货币交易属非法金融活动。

## 同系列 · Web3 防骗工具箱
全套 10 个 skill（蓝皮书蒸馏系列）：
- web3-wabcd-identifier
- token-concept-disambiguator
- compliance-redline-check
- three-mode-classifier
- co-build-community-ops
- risk-assessment-antipattern
- rwa-landing-path
- opc-individual-checklist
- regulation-hk-sandbox

完整索引见工具箱说明。
