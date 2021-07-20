## pull request하는 방법

1. 원하는 repo로 들어가 git branch로 main이 아닌 코드리뷰를 받을 branch를 생성한다.

2. git switch 로 해당 branch로 이동한다.

3. touch 를 이용해 파일을 생성한다. 
   - 이 때 문서 파일이면 .md를 java파일이면 .java를 양식에 맞게 생성한다.

4. 생성한 파일을 작성 혹은 수정한다.

5. git add, commit, push를 거쳐 github에 반영시킨다.

6. github에 들어가 해당 repo로 들어간 후 Manage access로들어가 코드리뷰를 받을 사람을 추가한다.

7. pull request로 들어가 create pull request를 눌러 생성해준다.
   - 이 때 base는 main  compare에 코드리뷰를 받을 branch를 설정한다.

8. 우측에 보이는 Reviewers에 코드리뷰를 해 줄 사람을 추가하고 create pull request를 해준다.
