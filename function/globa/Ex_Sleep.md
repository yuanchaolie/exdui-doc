# <a id="fun">[**Ex_Sleep --- 暂停程序的执行**](#index7)</a>

* ## <a id="1">Syntax / 函数原型</a>
	```C++
	void __stdcall 
	Ex_Sleep (
		int us
	);
	```
	---
* ## <a id="2">易语言声明</a>
	```Elang
	.版本 2

	.DLL命令 Ex_Sleep, , "libexdui.dll", "Ex_Sleep", 公开, 
		.参数 us, 整数型,  , 
	```
	---
* ## <a id="3">Parameters / 参数</a>
	| 参数名 | 参数类型 | 参数备注 |
	| --- | --- | --- |
	| `us` | **int** | `微秒 MicroSecond` |

	---

* ## <a id="4">Return Value / 返回值</a>
	|参数类型 | 参数备注 |
	|--- | ---|
	|int(整数型) | `暂停程序的执行`|
	---