===========
PEP-翻译项目
===========

格式
--------

所有翻译模块均为如下 **格式** , translation标签为段落标签，原文中若无<p>标签，则所有内容都在同一段：

    void main()
    {
        printf("Hello, Markdown.");
    }

    {% translation
    | 原文
    | 译文
    | 原文
    | 译文
    %}

该模块理想情况下应该以句为单位：

    | 原文
    | 译文

#### 4.4 代码区块
代码区块的建立是在每行加上4个空格或者一个制表符（如同写代码一样）。如
普通段落：

void main()
{
    printf("Hello, Markdown.");
}

代码区块：

    void main()
    {
        printf("Hello, Markdown.");
    }


PEP3333
-------

 * 地址：https://blog.instcode.top/Python/peps/pep-3333.html