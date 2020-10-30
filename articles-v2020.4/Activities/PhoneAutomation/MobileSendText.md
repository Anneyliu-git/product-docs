# 发送文本
将文本内容发送至光标所在处。
> 该组件仅能放置于**连接设备**组件内，且操作自动绑定至外层设备。
> 
> 在该组件前建议旋转点击等组件。
## 属性
### 基本
- **后延迟（毫秒）**：在执行组件操作之后的延迟时间（以毫秒为单位）。
- **前延迟（毫秒）**：：在开始执行组件操作之前的延迟时间（以毫秒为单位）。
- **失败后继续**：设置当此组件运行失败时，是否忽略此错误继续运行下一个组件。下拉框选择，当选择"是"时，如果该组件运行时遇到错误，该流程也会继续执行下一个组件，并不会停止；当选择"否"时，如果该组件运行时遇到错误，该流程将会停止执行并抛出错误。
- **显示名称**：默认为该组件的名称。支持更改，用户自定义此组件的显示名称。

### 输入
- **文本**：输入待发送的文本内容。

### 可选项
- **输入后回车**：输入文本后是否回车。选择“是”时，输入文本后自带一个回车符；选择“否”时，输入文本后无附加回车符。