# Codex Custom Pet: Reshiram

这个仓库存放一个可直接被 Codex 加载的自定义桌面宠物（Reshiram）。

## 目录结构

```text
.
├── .gitignore
├── README.md
└── reshiram/
    ├── pet.json
    └── spritesheet.webp
```

## 在 Codex 中使用

1. 把本仓库克隆到本机：

```bash
git clone <你的仓库地址> /Users/<你的用户名>/.codex/pets
```

2. 确认宠物目录存在：

```text
~/.codex/pets/reshiram/pet.json
~/.codex/pets/reshiram/spritesheet.webp
```

3. 重启 Codex App，并在宠物/头像浮窗里选择 `Reshiram`。


## 如果要继续修改宠物

成品使用不需要 `.venv`，但二次制作需要在当前机器重新创建虚拟环境并安装依赖（例如 `pillow`）。
