汉语趋向表达实验（正式实验冻结版 v19）

部署：将 index.html、assets 与 vendor 文件夹保持在同一级目录，整体上传到静态网站。
DataPipe Experiment ID：IRsUduBNRMIB
OSF Project：954m6
OSF Data Component：t835v
主试邮箱：devitsuk057@gmail.com

修订预试严格四格平衡链接：
?cell=1&phase=pilot2  EPT→AJT，A卷
?cell=2&phase=pilot2  EPT→AJT，B卷
?cell=3&phase=pilot2  AJT→EPT，A卷
?cell=4&phase=pilot2  AJT→EPT，B卷
未带 cell 参数时，任务顺序与题本独立随机。
phase 会写入数据，并作为上传文件名前缀。正式实验改用 phase=formal。

本版已修复：AJT每区组V1/V2/V3各2题；所有AJT填充题均有情境；EPT练习不重复正式图片；指导语和练习反馈；知情同意；ClozeCHI后休息；预实验反馈；失焦次数记录；EPT和AJT均按条件分块平衡随机，并记录题目呈现区块；实验材料采用限并发、自动重试和单文件超时的加载方式；DataPipe上传有超时和自动重试。

v19冻结内容：在v18基础上，正式链接缺少cell时阻止进入；图片预加载改为低并发、较长超时和自动重试；上传超时延长并采用递增重试；浏览器本地保存结构化CSV快照，服务器明确接收前不清除；重新打开页面时可尝试恢复上次未确认上传的数据。材料版本号为 final_v19_2026-08-07，素材缓存版本为 final-v9-20260807，题目随机化版本为 balanced-block-v2。ClozeCHI暂保留原始作答和完成率，待答案键确定后离线评分。
