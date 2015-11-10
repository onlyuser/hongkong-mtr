hongkong-mtr
============

Copyright (C) 2011-2015 Jerry Chen <mailto:onlyuser@gmail.com>

About
-----

hongkong-mtr is a graphviz dot specification for the Taipei MTR.
香港地鐵系統graphviz dot地圖.

A Motivating Example
--------------------

Radial:

[![picture alt](https://sites.google.com/site/onlyuser/files/hongkong-mtr_thumb.png "hongkong-mtr")](https://sites.google.com/site/onlyuser/files/hongkong-mtr.png)

Tree layout:

[![picture alt](https://sites.google.com/site/onlyuser/files/hongkong-mtr_tree_layout_thumb.png "hongkong-mtr")](https://sites.google.com/site/onlyuser/files/hongkong-mtr_tree_layout.png)

Requirements
------------

* graphviz dot

Installation (Debian)
---------------------

1. git clone https://github.com/onlyuser/hongkong-mtr.git
2. sudo aptitude install graphviz

Usage
-----

<pre>
neato hongkong-mtr.dot -Tpng -ohongkong-mtr.png
</pre>

References
----------

<dl>
    <dt>"MTR"</dt>
    <dd>https://en.wikipedia.org/wiki/MTR</dd>
</dl>

Keywords
--------

    HongKong MTR, dot, graphviz, graph search, 香港地鐵, 地鐵系統, 地鐵站, 地圖
