# MMT Altium 项目

此目录包含 2026-10-28 上传的本地 MMT 项目快照，入口为 `MMT.PrjPcb`。

**当前状态：已完成功能调试（项目作者确认，2026-10-28）。**

## 模块功能

MMT 是数控电源的电源输出与模拟控制模块，主要包括：

- `SMPS_POWER.SchDoc`：开关电源功率变换。
- `Bias_Power_Supply.SchDoc`：控制与模拟电路所需的辅助供电。
- `CC_CV_Down-programmer.SchDoc`：恒流 / 恒压控制及输出泄放。
- `CC_CV_Indicators_and_sense_error.SchDoc`：CC / CV 状态指示与采样异常相关电路。
- `DAC、ADC、IO_Espander.SchDoc`：输出设定、测量采样及数字 IO 扩展。
- `Bus isolators.SchDoc`：数字总线隔离与接口连接。
- `main.SchDoc`：模块顶层连接。

## 内容

- 7 张原理图（含 `main.SchDoc`）。
- PCB 文件 `数控电源.PcbDoc`。
- 工程配置、工程结构文件及两份输出任务配置。
- 已有导出文件 `MMT.pdf`。
- `Project Outputs for MMT/` 中已有的 DRC 检查报告。

## 未包含的文件

按项目所有者要求，不上传原理图库、PCB 封装库、集成库及其备份副本。Altium 的本地历史、日志和预览缓存也不包含在此快照中。

工程文件保留本地原始内容，可能仍引用未公开的库文件；需要更新或重新放置器件时，应自行配置所需库。输出任务中可能保留原电脑的绝对路径，换电脑运行前请检查路径。

PDF 和 DRC 报告为原目录中已有文件，本次上传没有重新生成它们，报告是否与当前设计同步需另行核对。“已完成功能调试”为项目作者提供的模块进度，不代表已完成整机联调、全部性能测试或安规认证。
