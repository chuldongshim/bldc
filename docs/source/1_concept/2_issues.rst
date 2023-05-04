===================
관리
===================

-------------------
이슈관리
-------------------

github를 통해 이슈관리를 수행한다.

open status
===================

다음 이슈는 github로 이관하여 관리될 예정임

.. collapse:: bldcissue01

  open_23.05.04, close_23.05.??
  build 폴더 버전관리에서 제외하고, github action으로 auto build해서 웹페이지 접속이 가능한지 확인

.. collapse:: bldcissue02

  open_23.05.04, close_23.05.??
  sphinx에서 줄바꿈

.. collapse:: bldcissue03

  open_23.05.04, close_23.05.??
  vscode 터미널에서 실행하는 ".\make clean; .\make html" 명령어 단축키로 실행 가능한지 확인

.. collapse:: bldcissue04
  
  open_23.05.04, close_23.05.??
  vscode rst extension으로 빌드 없이 미리보기 가능한지 확인


-------------------
형상관리
-------------------

링크
===================

url 링크
-------------------

사용법의 경우 사용법을 전부 직접 작성하기에는 시간이 많이 걸리므로 html을 저장해서 링크걸기

* `sphinx-collapse <https://pypi.org/project/sphinx_collapse/>`_
* `sphinx-toolbox <https://sphinx-toolbox.readthedocs.io/en/stable/index.html>`_

pdf 문서 링크
-------------------

`Virtualbox 사용법 <../_static/1_concept/2_issues/Virtualbox_how_to_use.pdf>`_

또한 사양서의 경우 markdown언어로 작성하기에는 한계가 있으므로 live script로 작성 후 pdf 포멧으로 _static 폴더에 저장한 다음 링크로 연결한다.
* mhtml로 변환하여 링크 연결 시 한글의 경우 글자깨짐 현상이 발생함
* simulink에서 요구사항과 live script 링크 연결이 가능하므로 사양서도 live script로 작성하는 것이 맞음


웹페이지
===================

확대/축소 고정
-------------------
크롬 설정 -> 모양 -> 페이지 확대/축소 설정
마이크로소프트 에지 설정 -> 브라우저 디스플레이 -> 페이지 확대/축소 설정