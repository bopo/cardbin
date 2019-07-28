=======
银行卡号验证库
=======


.. image:: https://img.shields.io/pypi/v/cardbin.svg
        :target: https://pypi.python.org/pypi/cardbin

.. image:: https://img.shields.io/travis/bopo/cardbin.svg
        :target: https://travis-ci.org/bopo/cardbin

.. image:: https://readthedocs.org/projects/cardbin/badge/?version=latest
        :target: https://cardbin.readthedocs.io/en/latest/?badge=latest
        :alt: Documentation Status

.. image:: https://pyup.io/repos/github/bopo/cardbin/shield.svg
     :target: https://pyup.io/repos/github/bopo/cardbin/
     :alt: Updates


* 开源协议: MIT license
* 在线文档: https://cardbin.readthedocs.io.

安装
--------
.. code-block:: console

    $ pip install cardbin

使用
--------
.. code-block:: console
    from cardbin.cardbin import valid
    valid('6222600260001072444')

    Out: {'bank': '交通银行', 'type': '太平洋借记卡'}

部署[docker]
--------
.. code-block:: console
    $ cd docker
    $ docker-compose up

功能
--------

* 完全支持 python3。 python2 将不再支持。
* 检查一个银行卡号是哪个银行，什么卡。
* 支持 zeromq 和 http 方式访问。
* docker 部署独立服务。

Credits
---------


