# SpellActivationOverlay_CNWotLK
Personal modified version

Start From [SpellActivationOverlay 1.3.2](https://github.com/ennvina/spellactivationoverlay/tree/v1.3.2)

# 修改原因
国服怀旧服目前插件接口的版本和海外插件接口版本不一致，导致海外 WLK 可用的插件无法在国服使用，或者有各种报错。

## Change Log
### 2025/3/22
- `options\InterfaceOptionsPanels.xml` 中使用了旧版的 `OptionsButtonTemplate` 和 `InterfaceOptionsFramePanelContainer`, 更换为新版的 `UIParent` 和 `UIPanelButtonTemplate`。