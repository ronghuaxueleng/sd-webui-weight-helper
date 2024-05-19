
<img src="https://github.com/nihedon/sd-webui-weight-helper/assets/66118290/f7079e1c-3b2a-426c-b3a2-1a7ccf57cab2" height="600px">

# Weight Helper Extension

## 概述

**Weight Helper** 是一个扩展，允许您通过鼠标操作直观地调整 Lora 和 Lyco 的权重。
您可以通过上下文菜单调整每个重量块的放大倍率。
注意：使用此扩展需要 LoRA 块权重扩展。

## 安装

1. 打开Stable Diffusion Web UI中的[扩展]选项卡。
2. 选择[从URL安装]。
3. 输入以下 URL 并执行安装。
```
https://github.com/ronghuaxueleng/sd-webui-weight-helper.git
```

## 用法

1. 右键单击 Lora 或 Lyco 标签以打开上下文菜单。
   - `<lora:lora_name:1.0>`
   - `<lyco:lyco_name:1.0>`
2. 移动权重滑块以调整每个砝码块的放大倍率。

## 特征

- 通过鼠标操作轻松设置权重值。
- 可以使用 `Lora Block Weight` 中的预设值.

## 配置选项

- 上下文菜单中的比例调整。
- 使用`execCommand` 使用函数进行文本替换（注意：`execCommand` 是一个已弃用的函数，但它允许“撤消”和“重做”）。
- 显示 `UNet`、`Dyn`、`Start` 和 `Stop` 滑块。
- 设置每个权重滑块的最小值、最大值和步长值。
- 详细设置`LBW` 的 `Lora` 和 `Lyco` 块的权重。

## 运行环境

- Stable Diffusion AUTOMATIC1111
- Windows
- Google Chrome

## 鸣谢

我们要对 `LoRA Block Weight` 的作者 `hako-mikan` 表示深深的感谢，感谢他创建了这个扩展。
```
https://github.com/hako-mikan/sd-webui-lora-block-weight
```

## License

该项目在 MIT 许可证下发布。
