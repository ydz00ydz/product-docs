# OCR 结果对比

OCR 结果对比组件用于通过数据表查看 OCR 识别结果并比对。

## 属性

### 配置

- **选择表**：下拉选择，任选一个本小程序应用中的数据表。
- **指定列**
  - 指定识别图列：下拉选择，选择该数据表中的某一列作为需要识别该列中的图。
  - 指定识别结果列：下拉选择，选择该数据表中的某一列作为将识别完成的结果保存至此列。
  - 指定状态列：下拉选择，选择该数据表中的某一列作为将识别完成的状态（true 代表通过，flase 代表不通过）保存至此列。
- **筛选**：配置一个或多个筛选项，支持按等于、不等于、包含、不包含、为空、不为空对条件列进行筛选。

### 样式

- **显示**：组件显示还是隐藏。
- **禁用**：组件禁用还是启用。
- **样式**：可选择“默认按钮”、“主按钮”、“警示按钮”、“文字按钮”这些样式，当调整字体、外观、边距时自动显示为“自定义样式”。
- **字体**：设置组件的字体样式及格式。
- **外观**：设置组件的外观样式。
  - **填充**：设置组件的填充颜色。
  - **边框色**：设置组件边框的颜色。
  - **边框样式**：设置组件边框的样式，是实线、虚线、点线还是双实线，以及线的粗细情况。
- **边距**：勾选“外边距”后，可调整该组件距离上下左右外边框的距离。
- **尺寸**：设置组件的宽度和高度。支持按像素（px）、百分比（%）、视口高度(vh)、视口宽度（vw）、自动（auto）进行缩放。

## 示例

1. 登录到 [小程序](https://apps.encoo.com/)。
2. 进入 **小程序开发** 的编辑模式。
3. 从左侧组件面板中选择 **模块组件** 下的 **OCR 结果对比** 组件，拖拽至画布中。
    ![添加 OCR 结果对比组件](https://docimages.blob.core.chinacloudapi.cn/images/Kris/AppsV2/OCRresultcomp20201208.png)

4. 单击 **预览** ，查看应用效果。
