<div align="center">

# 🎬 music-video-subtitle-generator

## 歌词贴字卡在鼓点上，15 秒一段也能拼成整支 MV
## Lyric typography that lands on the beat, cut by cut

📮 **商务合作 / Business：wow.vip@foxmail.com**
🎬 **抖音 / Douyin：[v.douyin.com/07EjIDGVErY](https://v.douyin.com/07EjIDGVErY/)**

</div>

---

## 🇨🇳 中文

这个技能根据音乐、歌词、参考图、角色、情绪和发布平台，制作带歌词贴字的风格化音乐视频或情绪短片。它先分析节拍与人声时序，区分人物、场景和文字三类参考，把屏幕文字当作设计图层来设计随节奏变化的空间字幕，再把长内容拆成连续镜头，默认交给 H3 批量生成，并围绕同一条主音轨完成拼接。锁定 prompt 与修订版本会写进 Design 画布文本节点，便于审阅。交付创意、分镜提示词、歌词方案与成片；不用于普通字幕校对、照搬现有版权形象或纯手工剪辑。

### ✨ 能做什么

- 分析节拍与人声时序 → 输出卡点切镜方案
- 把屏幕文字当设计图层：设计随节奏变化的空间字幕，而非普通字幕
- 超过 15 秒按多镜头拆解 + 首尾帧接续 + 鼓点硬切 + 全局主音轨对齐拼接
- 锁定 prompt 与修订版本写入 Design 画布文本节点，可审阅可回退
- 角色卡 / 场景卡 / 文字卡 / 视频片段 / BGM / 合成拆成输入输出清晰的独立阶段
- 没有歌词时先生成并锁定原创歌词，再进入视频生产

### 📦 包含的技能

- `music-video-subtitle-generator` —— 见 [`music-video-subtitle-generator/SKILL.md`](music-video-subtitle-generator/SKILL.md)

### 🚀 安装

```bash
git clone https://github.com/yzsp-studio/music-video-subtitle-generator.git
cp -r music-video-subtitle-generator/* "$DSH_HOME/skills/"
```

> 技能是**纯文本说明**（`SKILL.md` + `references/`），零依赖、零 API key，用你当前 agent 的会话额度。

---

## 🇬🇧 English

This skill builds stylized lyric-typography music videos or mood short films from music, lyrics, reference images, characters, mood, and target platform. It first analyzes beat and vocal timing, separates character, scene, and text references, and treats on-screen text as a design layer—spatial typography that shifts with the rhythm—then breaks long content into consecutive shots, generates in batches with H3 by default, and edits around a single master audio track. Locked prompts and revisions are written to Design canvas text nodes for review. It delivers creative direction, storyboard prompts, a lyric plan, and the finished video, and is not for ordinary subtitle proofing, copying existing copyrighted characters, or manual-only editing.

### ✨ What it does

- Analyzes beat and vocal timing to produce a cut-on-the-beat shot plan
- Treats on-screen text as a design layer: spatial typography that moves with the rhythm, not plain subtitles
- For clips over 15s, splits into multiple shots with first/last-frame continuity, hard cuts on the beat, and master-track alignment
- Writes locked prompts and revisions into Design canvas text nodes for review and rollback
- Separates character cards, scene cards, text cards, video clips, BGM, and compositing into stages with clear inputs and outputs
- Generates and locks original lyrics first when none are supplied, then moves into production

### 📦 Skills included

- `music-video-subtitle-generator` — [`music-video-subtitle-generator/SKILL.md`](music-video-subtitle-generator/SKILL.md)

### 🚀 Install

```bash
git clone https://github.com/yzsp-studio/music-video-subtitle-generator.git
cp -r music-video-subtitle-generator/* "$DSH_HOME/skills/"
```

> Skills are **plain-text instructions** (`SKILL.md` + `references/`). Zero dependencies, no API keys — they run on your agent's existing session quota.

---

## 📮 联系 / Contact

| | |
|---|---|
| 🎬 **抖音 / Douyin** | [https://v.douyin.com/07EjIDGVErY/](https://v.douyin.com/07EjIDGVErY/) |
| 📮 **商务合作 / Business** | **wow.vip@foxmail.com** |
| 🐙 **GitHub** | [https://github.com/yzsp-ai](https://github.com/yzsp-ai) |
| 💖 **打赏 / Support** | [afdian.com/a/yzsp-ai](https://afdian.com/a/yzsp-ai) |

## 📄 License

[MIT](LICENSE) · © 2026 [yzsp-ai](https://github.com/yzsp-ai)
