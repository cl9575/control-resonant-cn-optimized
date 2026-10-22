# CONTROL Resonant 简体中文翻译优化

# CONTROL Resonant — Simplified Chinese Translation Optimization

> 非官方简体中文文本优化，基于 **inkdesign** 的 [Simplified Chinese Localization Fix（CN Fix 16 v0.7）](https://www.nexusmods.com/controlresonant/mods/16) 二次修订。
>
> Unofficial Simplified Chinese text refinement built on **inkdesign**'s [Simplified Chinese Localization Fix (CN Fix 16 v0.7)](https://www.nexusmods.com/controlresonant/mods/16).

## 简介 / Overview

本项目的本体是 `base-zhcn.rmdtoc` 与 `base-zhcn-001.rmdblob`。在原作者 CN Fix 16 v0.7 的基础上，对范围内全部 **19,449 条**简中文本逐条对照英文复核，合并 **488 处**修正，覆盖任务、对白、档案、物品、界面、教程与协议文本。

This release refines the Simplified Chinese localization of CONTROL Resonant. Starting from inkdesign's CN Fix 16 v0.7, all **19,449** in-scope Chinese strings were re-checked against English, with **488** merged corrections across quests, dialogue, documents, items, UI, tutorials and protocols.

## 改动概览 / What changed

- 保留上一轮 **159 处**补校。
- 新增 **168 处**修正：前后用词或术语不一致，以及确实影响理解的误译（肯否或主客颠倒、对象或数量错误、整句漏译、原文没有的内容、错别字或残句）。
- **146 处** `CFD` 简称统一；首次解释的 3 处与 8 条收藏／美术条目名保留中文全称。
- **19 条**字幕时间轴校准（地下通道格里斯特场景＋达林训练录像带），只在已有标点处断句。
- 采纳 1 条官方更新译文；其余 58 条候选保持 mod 现状。
- 140 处润色类建议退回作者原文，语气、时态与措辞偏好未做风格性改写。

- **159** corrections carried over from the previous pass.
- **168** new corrections: inconsistent terminology and genuine mistranslations (reversed negation or subject/object, wrong referent or quantity, missing sentences, invented content, typos or broken fragments).
- **146** `CFD` abbreviation normalizations; the first three explanatory mentions and eight collection/artwork names keep the full Chinese name.
- **19** subtitle timeline fixes (Grist underground passage and Darling training tapes), only splitting at existing punctuation.
- 1 official updated line adopted; the other 58 candidates remain as in the mod.
- 140 stylistic suggestions rejected to preserve the original author's tone.

## 安装 / Installation

1. 备份游戏目录中的原文件（建议）。
2. 将 `base-zhcn.rmdtoc` 与 `base-zhcn-001.rmdblob` 覆盖到：
   `CONTROL Resonant\data_pack2\pc\`
3. 启动游戏，在设置中选择简体中文。

1. Back up the original files (recommended).
2. Copy `base-zhcn.rmdtoc` and `base-zhcn-001.rmdblob` into:
   `CONTROL Resonant\data_pack2\pc\`
3. Launch the game and select Simplified Chinese.

## 下载 / Download

在 [Releases](../../releases) 页面下载 `ControlResonant-CN-Optimized-v1.0.zip`。

Download `ControlResonant-CN-Optimized-v1.0.zip` from [Releases](../../releases).

## 校验 / Verification

- 回包后用独立解包器复读：24,968 个资源键顺序一致；除修正条目外，文本与基线逐字节相同；其余 5,573 个文件（含语音）逐字节相同。
- 文件 SHA-256 见 [`SHA256SUMS.txt`](SHA256SUMS.txt)，压缩包内也附有同一份校验文件。
- 游戏内显示与配音同步仍需实机确认。

- Re-extracted with an independent unpacker: 24,968 resource keys in identical order; all non-modified text byte-identical to the baseline; the other 5,573 files (including voice) byte-identical.
- SHA-256 checksums are in [`SHA256SUMS.txt`](SHA256SUMS.txt) and inside the zip.
- In-game display and voice sync still need confirmation on a real installation.

## 兼容性 / Compatibility

本项目基于 CN Fix 16 v0.7 的文件结构制作。若游戏后续更新改变了本地化容器的路径或结构，可能需要重新适配。

This project targets the file layout of CN Fix 16 v0.7. If a future game update changes the localization container path or structure, re-adaptation may be required.

## 署名 / Credits

- 原作者 / Original author: **inkdesign**
- 原 mod / Original mod: https://www.nexusmods.com/controlresonant/mods/16
- 作者主页 / Author profile: https://www.nexusmods.com/profile/inkdesign
- 基线版本 / Baseline: CN Fix 16 v0.7

本项目仅对原译文做二次修订，原译文版权归原作者所有。

This project only refines the original translation; all rights to the original translation belong to its author.

## 免责声明 / Disclaimer

非官方项目，与 Remedy Entertainment、505 Games 及 Nexus Mods 无关。若原作者对本项目有异议，将立即下架。

Unofficial project, not affiliated with Remedy Entertainment, 505 Games, or Nexus Mods. If the original author objects, this project will be taken down immediately.
