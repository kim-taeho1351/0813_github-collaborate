#github
git + hub
   * git:파일(코드)의 변화를 기록
   * github: git과 코드를 저장, 관리
   * 개발자의 포트폴리오 역활

#git 기본 명령어
   * **git init**    ->    git을 시작하겠다고 선언. 비어있는 로컬 git저장소를 만듬

   * **git remote add origin 원격저장소 주소**    ->    주소로 로컬과 원격저장소를 연결. origin은 주소의 이름

   * **git add .**    ->    git파일에 내용 추가. '.'는 모든 걸 추가한다는 뜻

   * **git commit -m ""**    ->    커밋을 해줌. '-m'은 ""안에 내용을 커밋의 설명으로 제공한다는 뜻

   * **git push origin master**    ->    origin 주소 원격저장소의 master 브랜치에 저장

   * **git branch**    ->    브랜치 목록 출력

   * **git branch 브랜치명**    ->    새로운 브랜치 생성

   * **git checkout 브랜치명**    ->    해당 브랜치로 이동

   * **git checkout -b 브랜치명**    ->    브랜치를 생성하여 이동

   * **git push origin 브랜치명**    ->    원격저장소의 특정 브랜치에 저장

   * **git pull origin 브랜치명**    ->    원격저장소의 특정 브랜치에서 변경사항 pull

   * **git clone 원격저장소 주소.git**    ->    원격저장소에 있는 파일 전체 복사

   * **git status**    ->    git저장소의 상태확인(파일의 커밋여부, 변경사항, 위치하고 있는branch 등을 출력)

처음: init -> remote -> add . -> commit -> push
다음부터: pull/clone -> 수정 -> add . -> commit -> push

<br><br>

>[02. Netlify](./Netlify.md)<br>
[03. collaborate](./collaborate.md)