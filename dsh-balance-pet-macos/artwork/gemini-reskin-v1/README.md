# Gemini 角色出图档案

Gemini 角色（蓝紫星纹装）的生成过程存档。最终成品即
[`Resources/sprite-gemini.png`](../../Resources/sprite-gemini.png)。

## 文件说明

- `prompt.txt` — 出图提示词：以原版蓝鲸女孩为编辑基准（identity-preserve），
  仅替换发色、虹膜配色、服装与尾巴，参考第二张图（蓝紫星纹角色）
- `cleanup-prompt.txt` — 二次清理提示词：去除背景光晕、保证透明 alpha，同时保留不透明黑色平板
- `character-v1.png` — 中间迭代稿
- `preview.html` — 本地预览页，引用 `character-v1.png`
- 最终成品图不在此目录存档，避免与 `Resources/` 重复；以 `Resources/README.md` 记录的哈希为准
