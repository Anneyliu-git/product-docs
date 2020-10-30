# 打开应用软件
打开手机上指定的应用软件。
## 属性
### 基本
-  **后延迟（毫秒）**：在执行组件操作之后的延迟时间（以毫秒为单位）。
-  **前延迟（毫秒）**：在开始执行组件操作之前的延迟时间（以毫秒为单位）。
-  **失败后继续**：设置当此组件运行失败时，是否忽略此错误继续运行下一个组件。下拉框选择，当选择"是"时，如果该组件运行时遇到错误，该流程也会继续执行下一个组件，并不会停止；当选择"否"时，如果该组件运行时遇到错误，该流程将会停止执行并抛出错误。
-  **显示名称**：默认为该组件的名称。支持更改，用户自定义此组件的显示名称。

### 目标
- **应用软件名**：Bundle Id的应用名称，系统自动生成，可编辑且可为空，并不做定位效用。
- **应用标识名**：应用软件的Bundle ID。