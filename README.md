# Christmas Tree 3D 交互式体验

使用gemini3创建的3D圣诞树交互式演示项目，结合了手势识别技术，让用户可以通过手势与圣诞树进行互动。

<img width="1932" height="1388" alt="d420be79f8ab8922ffb0fd831cddab21" src="https://github.com/user-attachments/assets/25d10780-4ccb-4b6a-8297-1f55dbe470f0" />
<img width="2754" height="1338" alt="f64d85e7f95f52d9a30bb27458c7cf83" src="https://github.com/user-attachments/assets/d5732164-031b-4c6b-b247-3853dd2a389a" />
<img width="1424" height="1334" alt="67bdebbf9312f593860cf21574a480de" src="https://github.com/user-attachments/assets/b5589dc9-fc04-4e74-9c42-dc23f9baf118" />
<img width="1748" height="1276" alt="64905909b736555c27cfd895bdc93d9a" src="https://github.com/user-attachments/assets/42e8448e-b63a-4639-92ef-ef9c116c48a2" />


## 使用方法

### 基本操作

1. **打开项目**
   - 在现代浏览器中直接打开 `christmas_tree.html` 文件即可运行（推荐Chrome浏览器）
   - 首次加载时会显示加载动画，请稍候

2. **上传照片**
   - 点击页面底部的"Upload Memories"按钮
   - 选择您想要展示的照片文件（支持jpg、png等常见图片格式）
   - 上传的照片会自动装饰在圣诞树上

### 手势控制（需要摄像头）

项目支持三种手势交互模式：

1. **握拳手势**
   - 做出握拳动作可切换显示模式
   - 在树形模式和文字模式间切换
   - 握拳也可让散落的装饰物回到树上

2. **捏合手势**
   - 拇指和食指靠近做出捏合动作
   - 可以聚焦查看特定的照片装饰
   - 聚焦的照片会放大并移至屏幕中央

3. **张开手掌**
   - 张开手掌让装饰物从树上散落
   - 装饰物会在3D空间中自由漂浮
   - 再次握拳可让装饰物回到树上

### 显示模式

- **树形模式**：装饰物附着在圣诞树上
- **文字模式**：装饰物重新排列成"MERRY CHRISTMAS"字样
- **散落模式**：装饰物在3D空间中自由分布
- **聚焦模式**：单独查看某一张照片

### 注意事项

- 为了获得最佳体验效果，请允许浏览器访问摄像头
- 项目会自动适应不同屏幕尺寸

## 🔗 致谢与来源 (Credits)

本项目的核心 Prompt 设计灵感来源于知乎文章，由 Gemini 协助生成与优化。

*   **Prompt 来源**: [gemini3手势互动圣诞树保姆级教程来了！附提示词](https://zhuanlan.zhihu.com/p/1981732280851506856)
*   **Tech Stack**: Three.js, MediaPipe, WebGL
