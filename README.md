# Copilot Skills

VS Code Copilot 用户级技能集合，跨项目通用。

## 技能列表

| 技能 | 用途 |
|------|------|
| [register-check](./register-check/SKILL.md) | MCU 寄存器配置校验（通用版）— 验证 PWM/ADC/GPIO/定时器等外设寄存器配置 |

## 新电脑上安装

```powershell
# 1. 克隆到用户技能目录
git clone https://github.com/h7tf4jc959-max/copilot-skills.git $env:USERPROFILE\.copilot\skills

# 2. 重启 VS Code → Copilot Chat 中自动加载
```

## 更新

```powershell
cd $env:USERPROFILE\.copilot\skills
git pull
```

## 目录结构

```
~/.copilot/skills/
├── register-check/
│   └── SKILL.md          # 通用版寄存器校验技能
├── (更多技能...)
└── README.md
```
