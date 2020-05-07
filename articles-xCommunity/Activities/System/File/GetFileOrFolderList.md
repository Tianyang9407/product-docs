# 获取文件/文件夹列表

获取指定路径下的文件或文件夹列表。同时提供选择&quot;遍历子文件夹&quot;选项和通配符筛选列表内容功能

## 属性

输入

- **路径** ：获取该路径下的文件或文件夹列表。支持相对和绝对路径。可在组件面板点击弹出对话框，选择要获取列表的路径；亦支持手动输入路径，若路径不存在，则运行失败。如果需要获取当前项目路径下的列表，则只输入双引号即可
- **列表模式** ：下拉框选择删除文件或文件夹
- **列表筛选** ：适用此筛选条件返回列表，支持通配符&quot;\*&quot; &quot;?&quot;。仅支持字符串变量和字符串
- **遍历子文件夹** ：勾选时，将同时获取指定路径子文件夹内的列表；不勾选时；则只获取指定路径内列表

输出

- **列表** ：将结果列表存储在此变量。返回类型为全路径