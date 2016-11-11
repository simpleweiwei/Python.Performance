# Python性能优化思路
## 注意跨平台的问题
【1】将Python转换为C（例如[Cython](http://cython.org/)、[Pyrex](http://www.cosc.canterbury.ac.nz/greg.ewing/python/Pyrex/)、[Pylnlne](http://pyinline.sourceforge.net/)——可在里边直接使用C）

【2】将Python转换为C++（例如[Nuitka](http://nuitka.net/)）

【3】将Python转换为机器码（例如Psyco）

【4】更换Python解释器（例如[PyPy](http://pypy.org/)）

【5】使用并发编程（多进程 or 并发框架）

