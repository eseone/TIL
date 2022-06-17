안녕하세요, 이세원입니다.



# markdown 필기

## Heading (#의 개수)

### ex) (#3개)

1. 하나
2. 둘
3. 셋

- `숫자` + `.` 으로 작성 가능.

  



- `내가 원하는 텍스트를 담을 수 있음` (` 요걸로)

- `*/-` + `space bar` 로 작성 가능

- `git config --global user.name <user_name>` : username

- ```
  git config --global user.email <email>
  ```

   : email

  - config는 내 로컬과 깃헙 계정을 연결시켜줄 때 1회만!!!!

- ```
  git init
  ```

   : 레포를 만들고 워킹 디렉토리랑 연결시켜줄때 최초 1회

  - 레포 만들때마다!
  - 여러분들이 레포를 만들때마다 계속 해주셔야한다.

- ```
  git status
  ```

   : 워킹 디렉토리에 어떤 변화가 있는지 알아보는 명령어.

  - 워킹 디렉토리 단계와 스테이징 에리아 단계의 변화

- `git add` + `.` : 전체 다 staging area로 올리기

- ```
  git add
  ```

   \+ 

  ```
  파일명.확장자
  ```

   : 이것만 올려

  - ex) `git add 파일1 파일2 파일3`

- ```
  git commit
  ```

   \+ 

  ```
  m
  ```

  ```
  "commit message"
  ```

  - 되도록 명령어로 적기
    - 동사형으로 시작하기
    - 영어로 적기
  - 약속일뿐 법은 아니다.

- ```
  git log --oneline
  ```

   : `` (하이픈) 두개입니다.

  - `commit`된 상황에서 어떤 메시지로 언제 뭐가 올라갔는지 알기위한 명령어

- ```
  git remote add
  ```

   \+ 

  ```
  origin <github 주소>
  ```

   : 내 워킹 디렉토리와 레포지토리 연결

  - `git remote -v` : 리모트가 잘 들어갔는지 확인

- `git push` + `origin master` : 최종으로 깃헙에 올린다!!!

1. `git config --global user.name / email` 잘 적었는지 확인

2. ```
   git remote 확인
   ```

   - `git remote add origin <깃헙 주소>`

3. `git add` 했는지

4. `git commit` 잘 했는지 확인





