# 中华人民共和国公司法综合知识库 Skill

一个用于 [Claude Code](https://claude.com/claude-code) 的中文公司法知识库技能(Skill),覆盖 **2023 年修订《公司法》**(2024 年 7 月 1 日施行)的法律解释、裁判规则与案例分析。

> 提炼自两本权威著作:
> - 最高人民法院民事审判第二庭《公司法理解与适用》(2024)——法律解释
> - 赵旭东《新公司法适用与最高人民法院公布案例解读》(2024)——案例分析
>
> 约 1,745 页 · 266 条 · 63 个案例

---

## ✨ 能做什么

把它装进 Claude Code 后,输入 `/company-law-spc-comprehensive`,即可:

- **按条文查询** —— 问「第 54 条」或「Art. 54」,返回法律解释 + 相关案例
- **按主题查询** —— 问「出资加速到期」「人格否认」「董事义务」,自动定位相关章节
- **按案例查询** —— 问「案例 24」或「Case 24」,加载该案例及法律分析
- **浏览目录** —— 问「有哪些章节?」查看完整索引
- **无参数调用** —— 加载核心框架与裁判规则作为参考

### 内置核心框架

时间效力三层次框架 · 有利溯及规则 · 股东出资义务体系 · 公司决议效力三层体系 · 越权担保效力判断 · 公司人格否认 · 董事义务体系 · 股权转让核心规则

### 章节一览

| # | 标题 | 关键框架与案例 |
|---|------|----------------|
| ch01 | 总则 | 越权担保、人格否认、决议效力三层体系 |
| ch02 | 公司登记 | 登记公示效力、涤除登记 |
| ch03 | 有限责任公司的设立与组织机构 | 出资加速到期、催缴义务、知情权 |
| ch04 | 有限责任公司的股权转让 | 优先购买权、未届期股权转让、异议股东回购 |
| ch05 | 股份有限公司的设立、组织机构、股份发行和转让 | 上市公司代持、发起人锁定期 |
| ch06 | 董事、监事、高级管理人员的资格和义务 | 忠实义务、勤勉义务、事实董事 |
| ch07 | 公司债券、财务与会计 | 债券持有人会议、利润分配请求权 |
| ch08 | 公司合并、分立、增资、减资 | 非同比例减资、违法减资、增资优先认缴权 |
| ch09 | 公司解散与清算 | 清算义务人、强制清算 |

---

## 📦 安装方法

> 前提:你的电脑已安装 [Claude Code](https://claude.com/claude-code)。

### 方式一:git clone(推荐)

```bash
cd ~/.claude/skills
git clone https://github.com/<你的用户名>/company-law-spc-comprehensive.git
```

### 方式二:下载压缩包

1. 在本仓库页面点击 **Code → Download ZIP**
2. 解压得到 `company-law-spc-comprehensive` 文件夹
3. 把整个文件夹放到:
   - **macOS / Linux**:`~/.claude/skills/company-law-spc-comprehensive`
   - **Windows**:`C:\Users\<用户名>\.claude\skills\company-law-spc-comprehensive`

> 💡 `.claude` 是隐藏文件夹。macOS 在 Finder 中按 `Cmd + Shift + .` 可显示隐藏文件;若没有 `skills` 文件夹,自行新建即可。

### 安装后使用

重启 Claude Code,输入:

```
/company-law-spc-comprehensive 第54条
```

---

## 📂 文件结构

```
company-law-spc-comprehensive/
├── SKILL.md          # 主入口(技能定义、核心框架、索引)
├── README.md         # 本文件
├── glossary.md       # 术语表
├── patterns.md       # 裁判规则与实务模式
├── cheatsheet.md     # 速查表
└── chapters/         # 9 个章节详解
    ├── ch01-general-provisions.md
    ├── ch02-company-registration.md
    ├── ch03-llc-establishment.md
    ├── ch04-equity-transfer.md
    ├── ch05-jsc-establishment.md
    ├── ch06-directors-duties.md
    ├── ch07-bonds-finance.md
    ├── ch08-merger-division.md
    └── ch09-dissolution-liquidation.md
```

---

## ⚖️ 来源与版权声明

- 本 Skill 内容由 **AI 从下列著作中提炼归纳**而成,用于**个人学习与交流**,不构成法律意见。
  - 最高人民法院民事审判第二庭《公司法理解与适用》(人民法院出版社,2024)
  - 赵旭东《新公司法适用与最高人民法院公布案例解读》(2024)
- 原著版权归原作者及出版社所有。本仓库**不包含原著扫描件或大段原文照录**,仅为框架、要点与裁判规则的二次归纳整理。
- 如著作权人认为本仓库内容不当,请提 Issue,将及时处理或删除。
- 法律法规与司法解释可能更新,实务中请以官方最新文本及具体个案为准。

---

## 🔄 适用法律版本

《中华人民共和国公司法》(2023 年修订,2024 年 7 月 1 日施行),并参考:
- 《全国法院民商事审判工作会议纪要》(九民纪要)
- 最高人民法院关于适用《公司法》若干问题的规定(一)至(五)
- 《关于适用〈民法典〉有关担保制度的解释》
- 《关于适用〈公司法〉时间效力的若干规定》
