# 客户体验与满意度管理顾问（开源版）

企业服务体验闭环的**判断层**方法与工具：定位体验断在哪一环、该先补哪一环、哪些投入现在不该做。

## 这是什么

本仓库是「客户体验与满意度管理顾问」的**开源源码**。内容为一整套可读、可改、可自取的方法与附表，核心是「六环自检」——把服务体验拆成发现、定位、派单、处理、验证、评估六环，逐环回答四个问题（有动作吗／有责任人吗／有人回头看吗／结论送回上一环了吗），答不上来的那一格就是断点。

配套附表：六环自检表、十问自测表、成熟度自评、报告模板、对话骨架、术语速查等（共 13 份，见 `src/judgement/references/`）。

## 目录结构

```
src/judgement/body.md            专家正文（判断层，完整可读，建议从这份读起）
src/judgement/references/*.md    附表（自检表 / 模板 / 速查）
assets/avatar-advisor.png        头像
LICENSE                          MIT
```

## 怎么用

**方式一 · 当方法读**：直接打开 `src/judgement/body.md`，按里面的判定顺序走一遍；要填表就把 `src/judgement/references/` 里对应的表打印出来。

**方式二 · 装成专家**：在 WorkBuddy、SkillHub、虾评任一平台搜索「客户体验与满意度管理顾问」安装，即可直接对话使用（平台版本由同一内容源构建，内容与本仓库一致）。

## 版本

| 项 | 值 |
|---|---|
| version | 4.1.0 |
| repo slug | `SLI-cx-satisfaction-advisor` |
| GitHub | `https://github.com/sunfan1014/SLI-cx-satisfaction-advisor` |

## 克隆

```bash
git clone https://github.com/sunfan1014/SLI-cx-satisfaction-advisor.git
```

## 许可

MIT，见 `LICENSE`。
