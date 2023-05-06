===================
관리
===================

------------------------
이슈관리
------------------------

github를 통해 이슈관리를 수행한다.

------------------------
형상관리
------------------------

github를 통해 소스(srcs) 및 산출물(docs) 관리를 수행한다. 

------------------------
문서작성
------------------------

일반문서작성
------------------------

프로젝트와 관련된 일반적인 내용은 sphinx를 통해 작성/관리/배포한다.

sphinx

* `Sphinx documentation <https://www.sphinx-doc.org/en/master/>`_
* `arduino esp32 documentation <https://docs.espressif.com/projects/arduino-esp32/en/latest/tutorials/blink.html#example-code>`_

sphinx theme

* `sphinx_rtd_theme <https://sphinx-rtd-theme.readthedocs.io/en/latest/installing.html>`_
* `sphinx_idf_theme <https://github.com/espressif/sphinx_idf_theme>`_


사양서작성
------------------------

또한 사양서의 경우 markdown언어로 작성하기에는 한계가 있으므로 live script로 작성 후 pdf 포멧으로 _static 폴더에 저장한 다음 링크로 연결한다.

(simulink에서 요구사항과 live script 링크 연결이 가능하므로 사양서도 live script로 작성하는 것이 맞음)

.. note:: mhtml로 저장하여 링크 연결 시 한글의 경우 글자깨짐 현상이 발생함
  
  문서링크 예: `Virtualbox 사용법 <../_static/1_concept/2_issues/Virtualbox_how_to_use.pdf>`_

------------------------
open status
------------------------

다음 이슈는 github로 이관하여 관리될 예정임

.. collapse:: bldcissue02

  open_23.05.04, close_23.05.??
  sphinx에서 줄바꿈

.. collapse:: bldcissue03

  open_23.05.04, close_23.05.??
  vscode 터미널에서 실행하는 ".\make clean; .\make html" 명령어 단축키로 실행 가능한지 확인

.. collapse:: bldcissue04
  
  open_23.05.04, close_23.05.??
  vscode rst extension으로 빌드 없이 미리보기 가능한지 확인


