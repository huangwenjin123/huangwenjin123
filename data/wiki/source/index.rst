.. User Manual documentation master file, created by
   sphinx-quickstart on Mon Oct 11 15:27:11 2021.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.
   
用户手册
==============
.. toctree::
   :maxdepth: 2

   install
   support

目录1
======================================

* `提交作业`
* `ssh`
* `图形应用`

目录2
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

测试
====================

斜体： *text*

加粗: **text**

代码块：``text``

.. code-block:: python
   :linenos:
   
   module add intel/2019b
   export PATH=$PATH:/public/software/.local/easybuild/software/VASP/vasp/vasp.5.4.4/bin
   ulimit -s unlimited
   ulimit -l unlimited
   mpirun vasp_std

图片测试
==============
**北鲲云超算**

https://www.cloudam.cn/index.html

.. image::photo/cloudE138.png
   :height: 100px 
   :width: 200 px 
   :scale: 50 % 
   :alt: 替代文本
   :align: right
   
