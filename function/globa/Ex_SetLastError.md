# <a id="fun">[**Ex_SetLastError --- 设置最后错误代码**](#index6)</a>

* ## <a id="1">Syntax / 函数原型</a>
	```C++
	void __stdcall 
    Ex_SetLastError (
        int nError
    );
	```
	---
* ## <a id="2">易语言声明</a>
	```Elang
    .版本 2

    .DLL命令 Ex_SetLastError, , "libexdui.dll", "Ex_SetLastError", 公开,
        .参数 nError, 整数型,  , 
	```
	---
* ## <a id="3">Parameters / 参数</a>
	| 参数名 | 参数类型 | 参数备注 |
	| --- | --- | --- |
	| `nError` | **int** | `错误代码 参见` [ERROR_EX_]("#") |

	---

* ## <a id="4">Return Value / 返回值</a>
	|参数类型 | 参数备注 |
	|--- | ---|
	|int(整数型) | `设置最后错误代码`|
	---