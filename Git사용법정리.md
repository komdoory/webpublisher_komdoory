# 웹퍼블리셔과정 20200727-20201218

[마크다운내용](./A_ASSIST/A_MARKDOWN.MD)

1. git 계정 생성하기

2. new repository 생성

3. 내컴퓨터에서 got clone 생성한 repository :$ git clone https://github.com/komdoory/webpublisher_komdoory.git / (결과) Administrator@G501-13 MINGW64 /c/KOMDOORY_Work/webpublisher_komdoory (master) : Git과 연결되었다는 의미 확인

4. README.md 파일을 생성 및 내용 작성 : $touch로 타이포라 파일 하나 만들어주고 내용 입력하고

   (결과) $ cat README.md : (캣아이) 저장되었나 확인함

5. push/pull 이전에 계정을 연결 (아래 택배순서)

   - config 설정 :보낼때

   1. 자료를 올리는 사람의 이름과 이메일 주소

      :사용자 이름 설정 (configuration)
      $ git 

      $ git config --global user.name "komdoory"
      --global :컴퓨터 자체에 설치하겠다는 것

      안쓰면 : 내가 있는 파일에만 only 해당됨

      $ git config --global user.name "komdoory"
      $ git --global user.email "vanessakang2015@gmail.com"

      확인 : $ git --global user.email / $ git config user.name

   2. 계정 id /pw 

6. github로 push (보내겠다) 처리하여 보내기

   <수시체크 git status>

   git add (파일 폴더 모두의 수정, 삭제 애드 모두)

   git commit -m "설명"

   git push

   끝

7. github의 자료를 pull (가져오기) 처리하여 가져오기

---

## 택배보내는순서

1. 물건을 포장한다 : 파일을 만든다
2. 상자에 담는다 : $ git status로 확인 -> $git add 파일이름

1. 우체국에 간다

2. 송장 작성 (내용설명: commit)=고유번호화

   :$ git commit -m (썸머리의 m) "생성을위한첫파일"(예시-수정불가) : 내용설명

3. 물건 보내기 : $ git push -> git 로그인창 뜸 (또는 자동저장된 것으로 자동 웹GITHUB저장)

   이제 동기화 되었음

---

내용 변경후 저장하고

다시 git bash에서 

$ git status

- modified (red)
- $ git add readme.md



---

한번 저장하면 변하지 않는 것 (컴퓨터 바뀌지 않는 이상)

1. github가입

2. 저장소 생성 Repositories

3. git config --global user.name "사용자이름"

   got config --global user.email "사용자이메일"

4. git push 설정시 id/pw
   
   * 컴퓨터에서 계정 로그아웃: 제어판 =사용자계정=자격증명관리자=윈도우자격증명/ 아래에 git 계정 삭제

