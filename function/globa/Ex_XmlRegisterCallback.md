# <a id="fun">[**Ex_XmlRegisterCallback --- 注册XML键值回调**](#index9)</a>

* ## <a id="1">Syntax / 函数原型</a>
	```C++
    void __stdcall 
    Ex_XmlRegisterCallback (
        int atomValue,
        int pfnCallback
    );
	```
	---
* ## <a id="2">易语言声明</a>
	```Elang
    .版本 2

    .DLL命令 Ex_XmlRegisterCallback, , "libexdui.dll", "Ex_XmlRegisterCallback", 公开, 
        .参数 atomValue, 整数型,  , 
        .参数 pfnCallback, 子程序指针,  , 
	```
	---
* ## <a id="3">Parameters / 参数</a>
	| 参数名 | 参数类型 | 参数备注 |
	| --- | --- | --- |
	| `atomValue` | **int** | `原子值` |
	| `pfnCallback` | **int** | `回调函数`|
	---

* ## <a id="4">Return Value / 返回值</a>
	|参数类型 | 参数备注 |
	|--- | ---|
	|int(整数型) | `注册XML键值回调`|
	---