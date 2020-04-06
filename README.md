# Task 01 - repository, branch, commit

Repository
---

Repository란 저장소라는 뜻으로, 말 그대로 파일이나 폴더를 저장해 두는 곳이다. 모든 프로젝트는 각각의 repository가 있으며, URL로 접근이 가능하다.
Git 저장소는 특히 파일이 변경 이력 별로 구분되어 저장되는데, 이 경우 비슷한 파일이라도 실제 내용 일부 문구가 서로 다르면 다른 파일로 인식하기 때문에 파일을 변경 사항 별로 구분해 저장할 수 있는 장점이 존재한다.

#### 원격 저장소와 로컬 저장소

##### 원격 저장소?
: 파일이 원격 저장소 전용 서버에서 관리되며 여러 사람이 함께 공유하기 위한 저장소

##### 로컬 저장소
: 내 PC에 파일이 저장되는 개인 전용 저장소

Branch
---

Branch란 독립적으로 어떤 작업을 진행하기 위한 개념이며, 여러 개발자들이 동시에 다양한 작업을 할 수 있게 만들어주는 기능이다. 각 Branch들은 다른 Branch의 영향을 받지 않기 때문에, 각자 독립적인 작업 영역(저장소) 안에서 소스코드를 변경할 수 있게 된다. 

#### master branch?
: Repository를 처음 생성하면 만들어지는 Branch이다. 다른 Branch를 만들어서 선언(checkout)하지 않는 이상, 모든 작업은 'master' 브랜치에서 이루어지게 된다.

