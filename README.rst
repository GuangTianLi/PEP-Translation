===========
PEP-翻译项目
===========

格式
--------

所有翻译模块均为如下 **格式** , translation标签为段落标签，原文中若无<p>标签，则所有内容都在同一段：


.. code::

    {% translation
    | This is a sentence.
    | 这是一句话。
    | This is another sentence.
    | 这是另一句话
    %}


该模块理想情况下应该以句为单位：

.. code::

    | This is a sentence.
    | 这是一句话。

支持html标签：

.. code::

    | This is <strong>a sentence</strong>.
    | 这是<strong>一句话</strong>。


PEP3333
-------

 * 地址：https://blog.instcode.top/Python/peps/pep-3333.html