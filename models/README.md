# models

- `u2netp.onnx` — U²-Net（軽量版 u2netp）。写真の主役のモノだけを切り抜くのに使う（「マップで遊ぶ」の「モノを撮る」）。
  - 元: U-2-Net（Xuebin Qin ほか）https://github.com/xuebinqin/U-2-Net — Apache License 2.0
  - ONNX 版は rembg（https://github.com/danielgatis/rembg）の配布物
- `mobilenetv2-12-int8.onnx` — MobileNetV2（ImageNet 1000種類、int8）。切り抜いたモノが何か（キーボード・マグカップ・ぬいぐるみ・くつ…）を見分けて、足場の効果を決めるのに使う
  - 元: ONNX Model Zoo https://github.com/onnx/models（validated/vision/classification/mobilenet）— Apache License 2.0
