# Command＋D 快捷键提示

5.5秒、1080×1920、30fps 的独立静音 Remotion 动效。

## 运行

Node.js 22+。

```sh
npm ci
npm start
npm run render
```

在 index.tsx 修改按键数组、按住起止时刻及 accent 配色。内嵌字体为演示文本子集；新增中文时应重新制作子集或换用许可允许的完整字体，系统字体仅作后备。

## 来源与许可

基于自制真人口播融合样片中内联编写的Command＋D 快捷键提示效果提取和重新编排，使用 Codex 整理为独立工程。演示文案已通用化，不包含真人、原声、私人路径或检测结果。快捷键仅作组合键视觉示意，不承诺某软件的具体响应。

不包含 Overlay Studio、video-talkcraft 的卡片源码或 schematic 模块，不包含 Shotcraft 运镜组件、第三方设备模型及系统截图。仅 React/Remotion 作为运行依赖，遵循各自许可。

自有动效源码 MIT，见 LICENSE。字体为 Adobe Source Han Sans 的重命名子集，嵌入 fontData；SIL OFL 1.1 见 OFL.txt。本仓库 MIT 不覆盖字体及运行依赖。
