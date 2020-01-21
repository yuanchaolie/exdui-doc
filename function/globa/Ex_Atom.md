# <a id="fun">[**Ex_Atom --- '字符串取原子号'**](./index.md?#index1)</a> #

* ## <a id="1">Syntax / 函数原型</a>
    ```C++
    int __stdcall 
    Ex_Atom (
        LPCTSTR lptstring
    );
    ```
    ---
* ## <a id="2">易语言声明</a>
    ```Elang
    .版本 2

    .DLL命令 Ex_Atom, 整数型, "libexdui.dll", "Ex_Atom", 公开,
        .参数 lptstring, 整数型,  , 
    ```
    ---
* ## <a id="3">Parameters / 参数</a>
    | 参数名 | 参数类型 | 参数备注 |
    | --- | --- | --- |
    | `lptstring` | **LPCTSTR** | `传入的字符串` |

    ---

* ## <a id="4">Return Value / 返回值</a>
    |参数类型 | 参数备注 |
    |--- | ---|
    |int(整数型) | `获取字符串唯一原子号`|
    ---
    