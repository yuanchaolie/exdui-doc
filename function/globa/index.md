# <a href="./index.md">**函数目录索引--全局函数**</a> #

| **函数名** | **函数原型** | **函数声明** | **函数参数** | **函数返回** | **函数备注** |
| ----- | ----- | ----- | ----- | ----- | ----- |
| <a id="index1">[Ex_Atom](./Ex_Atom.md#fun)</a> | [C函数原型](./Ex_Atom.md?#1) | [E函数声明](./Ex_Atom.md?#2) | [(LPCTSTR lptstring)](./Ex_Atom.md?#3) | [**int32(整数型)**](./Ex_Atom.md?#4) | 字符串取原子号 |
| <a id="index2">[Ex_GetLastError](./Ex_GetLastError.md?#fun)</a> | [C函数原型](./Ex_GetLastError.md?#1) | [E函数声明](./Ex_GetLastError.md?#2) | ["空"]() | [**int32(整数型)**](./Ex_GetLastError.md?#4) | 获取最后错误代码 |
| <a id="index3">[Ex_Init](./Ex_Init.md?#fun)</a> | [C函数原型](./Ex_Init.md?#1) | [E函数声明](./Ex_Init.md?#2) | ["空"]() | [**bool(逻辑型)**](./Ex_Init.md?#4) | 初始化引擎<br>使用 ExDUI 前，请务必调用 Ex_Init。 |



<br><br><br>
=====================================================================
[^_^]:我是Ex_Init --- '初始化引擎'
# <a id="fun3">[**Ex_Init**](#index3)</a>

* ## [Ex_Init --- '初始化引擎'](#index3)
  
    1. <a id="fun3.1">Syntax / 函数原型</a>
        ```C++
        bool __stdcall 
        Ex_Init (
            HINSTANCE hInstance,
            DWORD     dwGlobalFlags,
            HCURSOR   hDefaultCursor,
            LPCTSTR   lpszDefaultClassName,
            LPVOID    lpDefaultTheme,
            DWORD     dwDefaultThemeLen,
            LPVOID    lpDefaultI18N,
            DWORD     dwDefaultI18NLen
        );
        ```
        ---
    2. <a id="fun3.2">易语言声明</a>
        ```Elang
        .版本 2

        .DLL命令 Ex_Init, 逻辑型, "libexdui.dll", "Ex_Init", 公开,
            .参数 hInstance, 整数型,  ,
            .参数 dwGlobalFlags, 整数型,  ,
            .参数 hDefaultCursor, 整数型,  ,
            .参数 lpszDefaultClassName, 整数型,  ,
            .参数 lpDefaultTheme, 整数型,  ,
            .参数 dwDefaultThemeLen, 整数型,  ,
            .参数 lpDefaultI18N, 整数型,  ,
            .参数 dwDefaultI18NLen, 整数型,  ,
        ```
        ---
    3. <a id="fun3.3">Parameters / 参数</a>
        | 参数名 | 参数类型 | 参数备注 |
        | --- | --- | --- |
        | `lptstring` | **LPCTSTR** | `传入的字符串` |
        | `hInstance` | **HINSTANCE** | `动态库(DLL)的实例句柄 可为NULL` |
        | `dwGlobalFlags` | **DWORD** | `全局初始化标识 参见` [EXGF](../../const/EXGF.md) |
        | `hDefaultCursor` | **HCURSOR** | `默认鼠标指针句柄 可为NULL` |
        | `lpszDefaultClassName` | **LPCTSTR** | `默认窗口类名 可为NULL` |
        | `lpDefaultTheme` | **LPVOID** | `默认主题包指针` |
        | `dwDefaultThemeLen` | **DWORD** | `默认主题包缓冲区长度` |
        | `lpDefaultI18N` | **LPVOID** | `默认语言包指针`  |
        | `dwDefaultI18NLen` | **DWORD** | `默认语言包指针缓冲区长度` |
        ---

    4. <a id="fun3.4">Return Value / 返回值</a>
        参数类型 | 参数备注 
        --- | ---
        BOOL(逻辑型) | `初始化引擎`
        ---
    5. 备注<br>
        使用 ExDUI 前，请务必调用 Ex_Init。
        具体使用方法去dome中查看




