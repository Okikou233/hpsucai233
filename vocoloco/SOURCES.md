# VocoLoco 来源

- VocoLoco 源码：https://github.com/Magkino/vocoloco_tts ，提交 7fa8601b9864005e473e14b41756d6e963211d97，Apache-2.0。此目录保留其 LICENSE。
- workers/tts-worker.js 只改动 ONNX Runtime 加载地址，使运行时文件从本站提供。
- ONNX Runtime Web 1.30.0：MIT，来自 npm onnxruntime-web。
- 模型：https://huggingface.co/Gigsu/vocoloco-onnx ，修订 2c301ff95a826f76ec9ff3d93233318f91362bf5。
- OmniVoice 权重：CC BY-NC；Higgs Audio v2 编码器及解码器使用 Boson Higgs Audio 2 Community License；Whisper large-v3-turbo 为 MIT。实际发布前核对各自模型卡的最新条件。
