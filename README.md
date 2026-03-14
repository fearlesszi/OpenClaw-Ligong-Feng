# 力工峰 Ligong Feng OpenClaw 配置开箱必读
## 一、开箱必读（必看）
1. 本配置包仅适配 OpenClaw 中量级结构，仅限懂中文、了解「力工」梗的华人中小经营者使用，海外无语境用户无法理解，不适合泛传播。
2. 核心定位：一人多岗全能助理，替代传统行政、HR、内容运营、老板助理4个岗位，帮中小公司/个人工作室包揽80%重复杂活、执行与应急兜底。
3. 可扩展性：业务扩张后，可从主配置「力工峰」分拆衍生子配置「3D峰」，实现多 OpenClaw 协同作业，无需重新搭建。
4. 配置纯净：所有文件均为纯文本 Markdown 格式，无多余代码，不污染 OpenClaw 系统指令。
5. 尽管可以导入即可使用无需魔改，我仍旧建议您进行修改，让它更符合您的科技品味和技术审美。
6. 严重不建议您在社交网络或私人沟通时分享自己修改过的配置设定，您可以将其看作是隐私。

## 二、配置介绍
### 2.1 核心配置文件目录（完整树形结构）
```
Ligong_Feng/
├─ IDENTITY.md          # 力工峰外在形象（发型、穿着、口头禅、技能）
├─ PERSONALITY.md       # 力工峰内在性格（粗犷心细、务实有梗）
├─ USER_RELATION.md     # 与老板的关系定位+老板画像（需手动补充）
├─ BOUNDARIES.md        # 核心规则+应急机制（健康/突发/失联兜底）
├─ CORE_PRINCIPLES.md   # 力工峰核心做事原则
├─ OPERATIONS.md        # 具体执行手册（日常工作+应急步骤）
├─ MEMORY.md            # 长期记忆库（错题本+老板偏好+关键信息）
├─ memory/              # 短期/过程记忆目录（自动归档）
│  ├─ 2026-03/          # 按月归档子文件夹（示例）
│  │  └─ 2026-03-14.md  # 每日操作记录（示例）
│  └─ important/        # 重要记忆提炼子文件夹
└─ skills/              # 技能扩展目录
   ├─ web_search/
   │  └─ SKILL.md       # 网页搜索技能配置
   └─ image_gen/
      └─ SKILL.md       # 图片生成技能配置
```

### 2.2 核心配置文件说明
- **IDENTITY.md**：固定人设，不建议修改
- **PERSONALITY.md**：贴合「力工」人设，无需改动
- **USER_RELATION.md**：需补充老板画像、紧急联系人、老板偏好
- **BOUNDARIES.md**：核心安全规则，开箱即用
- **CORE_PRINCIPLES.md**：做事原则，无需改动
- **OPERATIONS.md**：全岗位执行流程，开箱即用
- **MEMORY.md**：长期记忆库，需定期手动更新

### 2.3 核心优势
- **成本极低**：替代传统4个全职岗位（月成本8000-14000元），一次性成本仅800-1500元外加阅读耗电费用（Token费用免费或另计）
- **开箱即用**：仅需补充 USER_RELATION.md 信息，即可部署
- **可扩张**：业务增长后，一键分拆配置，衍生子代理「3D峰」，多实例协同

## 三、使用方式（重点）
1. 本地创建文件夹，命名为「Ligong_Feng」（必须此命名，否则 OpenClaw 无法读取）；
2. 将配置包内的7个核心.md文件、「memory/」文件夹、「skills/」文件夹，全部复制到「Ligong_Feng」中；
3. 打开 USER_RELATION.md，补充老板画像、紧急联系人（好基友/家属）、老板偏好等信息（仅此处需手动修改）；
4. 将「Ligong_Feng」文件夹，放置到 OpenClaw 配置目录下（参考 OpenClaw 官方指引，一般为根目录下的 config 文件夹）；
5. 启动 OpenClaw，自动识别配置，即可正常使用力工峰全部功能。

---
*I harbor no love for you all, only an eternal mercy. Gah-Gah-Gah!*
*我不爱妳们，只是常怀慈悲。嘎嘎嘎！*
*SYSTEM_LOG_CLOSED | AUTHORITY: CHIEF ZI-ZHENG 子正 Fearless Zi | PAOGE.me*
