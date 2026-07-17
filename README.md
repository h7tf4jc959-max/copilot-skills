# Copilot Skills

VS Code Copilot 用户级技能集合，跨项目通用。

## 技能列表

| 技能 | 用途 |
|------|------|
| [register-check](./register-check/SKILL.md) | MCU 寄存器配置校验 — 验证 PWM/ADC/GPIO/定时器等外设寄存器配置 |
| [waveform-analyze](./waveform-analyze/SKILL.md) | 波形分析 — 解析 Saleae Logic .sal 文件，分析 EMS/PWM/GPIO 时序 |

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
│   └── SKILL.md              # MCU 寄存器配置校验
├── waveform-analyze/
│   └── SKILL.md              # 波形分析 (Saleae Logic .sal)
└── README.md
```
