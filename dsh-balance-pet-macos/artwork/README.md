# artwork · 素材出图档案

存放各角色素材的生成过程档案：提示词、中间稿、清理脚本提示等。
**实际打进应用的成品图在 [`Resources/`](../Resources/README.md)**，来源与哈希也记录在那里。

## 目录

| 目录 | 内容 |
| --- | --- |
| [`left-completion-v1/`](left-completion-v1/README.md) | 蓝鲸女孩左侧（尾巴/尾部构图）补全的出图档案 |
| [`character-variants-v1/prompts/`](character-variants-v1/prompts/) | Claude / Gemini / GPT 三位角色的第一版提示词；`kimi.txt` 为当时一并尝试、**未采用上线**的 KIMI 版角色草稿 |
| [`character-variants-v2/prompts/`](character-variants-v2/prompts/) | 同三位角色的第二版提示词，在第一版基础上补充`以新的单人物参考图为准、忽略其姿势/表情/道具`的说明 |
| [`gemini-reskin-v1/`](gemini-reskin-v1/README.md) | Gemini 角色单独精修（identity-preserve 换装换色）的出图档案 |

提示词均为英文（出图模型输入），带说明的 README 用中文。
