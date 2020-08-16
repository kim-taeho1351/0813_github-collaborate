# Collaborator를 이용한 협업
1. 원격저장소 생성(github repository 생성)

2. 팀원을 collaborator로 추가
   * Settings -> Manage access -> invite a collaborator -> 팀원들의 계정 찾아서 add
   * 초대받은 팀원은 github에 연결된 이메일에서 초대 수락
3. 초기 프로젝트 push

4. 팀원들의 로컬에 프로젝트 pull
   * git clone 원격저장소 주소

5. 팀원 각자의 브랜치를 생성하여 작업
   * 팀원들 각각 자신의 이름으로 독립 breanch 만들어서 작업
6. 브랜치에 작업한 내용 push
   * 자신의 이름 branch에 push(**master에 push X**)

7. master와 merge 하기 전 pull request
   * Pull request탭 -> New pull request -> base, compare 브랜치 설정(compare -> base) -> 메세지 작성 -> Creat pull request

8. pull request 확인 후 master와 merge
   * 팀장이 변경사항 확인 후 괜찮을 때 Merge pull request -> Confirm merge

<br><br>

# Fork를 이용한 협업
1. 작업하고싶은 Repository fork 해오기
   * 해당 Repository 오른쪽 위 포크버튼 클릭 -> 작업할 자신의 Repository선택

2. 자신의 로컬에서 작업
   * clone

3. 변경사항을 자신의 브랜치에 push

4. 원본 레포지토리 소유자에게 pull request요청
   * base repository, head repository, base branch, compare branch 설정
   * base repository base branch <- head repository compare branch

5. 소유자가 pull request를 승인하여 merge하면 자동으로 collaborator 추가

<br><br>

>[01. github](./github.md)<br>
[02. Netlify](./Netlify.md)<br>