==============================
MongoEngine User Documentation
==============================

**MongoEngine**은 MongoDB를 이용하기 위해 파이썬으로 작성된 객체와 Document를 매핑해주는 라이브러리입니다.
간단하게 설치하고 실행할 수 있습니다.

.. code-block:: console

    $ pip install -U mongoengine

:doc:`tutorial`
  MongoEngine을 이용하여 tumblelog을 만드는 튜토리얼입니다.

:doc:`guide/index`
  documents를 모델링 하는 것부터 파일을 저장하는 것까지 그리고 데이터를 query하는 것 등 MongoEngine에
  대한 *전체적인* 가이드입니다.

:doc:`apireference`
  documents, querysets, fields의 내부에 대한 전체적인 API 문서입니다.

:doc:`upgrade`
  어떻게 MongoEngine을 업그레이드 하는지에 대한 문서입니다.

:doc:`django`
  Django 내에서의 MongoEngine 사용법에 대한 문서입니다.

**MongoEngine** is an Object-Document Mapper, written in Python for working with
MongoDB. To install it, simply run

Community
---------

MongoEngine을 사용하는 데에 있어 도움이 필요하다면 `MongoEngine 사용자 google 그룹스
<http://groups.google.com/group/mongoengine-users>`_ 를 이용하거나
`stackoverflow <http://www.stackoverflow.com>`_ 를 이용하세요.

Contributing
------------

**Yew please!**  우리는 언제나 추가와 발전을 위한 컨트리뷰션을 기다리고 있습니다.

MongoEngine의 소스는 `GitHub <http://github.com/MongoEngine/mongoengine>`_ 에 있습니다.
그리고 언제나 이 문서, 웹사이트, 내부구조에 대한 컨트리뷰션을 격려하고 있습니다.

컨트리뷰션은 `GitHub <http://github.com/MongoEngine/mongoengine>`_ 에서 포크를 한 다음
풀 리퀘스트를 보내주세요.

Changes
-------

MongoEngine에 대한 모든 변경 사항들은 :doc:`changelog`에서, 모든 업그레이드 사항들은
:doc:`upgrade`에서 확인할 수 있습니다.

.. note:: 항상 `upgrade <upgrade>`_ 문서를 읽고 실제 배포 되기 전에 읽고 테스트 해주세요! **;)**

Offline Reading
---------------

`pdf <https://media.readthedocs.org/pdf/mongoengine-odm/latest/mongoengine-odm.pdf>`_ 또는
`epub <https://media.readthedocs.org/epub/mongoengine-odm/latest/mongoengine-odm.epub>`_ 에서
오프라인에서 이 문서를 다운로드할 수 있습니다.

.. toctree::
    :maxdepth: 1
    :numbered:
    :hidden:

    tutorial
    guide/index
    apireference
    changelog
    upgrade
    django

Indices and tables
------------------

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

