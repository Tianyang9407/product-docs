# 打开程序

用于启动指定的应用程序并在其中执行多个组件。（可选）它可以将参数列表传递给应用程序。

## 属性

程序

- **文件名** ：打开此路径下的可执行文件。可通过点击&quot;指定程序&quot;自动生成。例如要打开Excel,则可填入类似：&quot;C：\Program Files\Microsoft Office\root\Office16\EXCEL.EXE&quot;。仅支持字符串变量和字符串
- **选择器** ：定位指定程序进行打开。可通过点击&quot;指定程序&quot;自动生成。若不使用&quot;指定程序&quot;，手动填写&quot;文件名&quot;（即此项为空时），则无法实现最大化功能且输出程序变量为空

- **参数** ：启动程序时可以传递给应用程序的参数。可以使用此属性使用您要打开的应用程序打开特定的文件.例入要打开特定的Excel工作簿，则可添加其完整路径：&quot;C:\Users\currentuser\Documents\Sample.xlsx&quot;
- **工作目录** ：目标程序的工作目录。如果在文件名中已给出，则无需填写此项

选项

- **最大化** ：将打开的程序最大化

输出

- **程序** ：将目标程序存储在此变量。可作为&quot;关闭程序&quot;的输入值
