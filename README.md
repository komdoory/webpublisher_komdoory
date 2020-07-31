# 웹퍼블리셔과정 20200727-20201218

1. git 계정 생성하기

   ---

   333

2. new repository 생성

3. 내컴퓨터에서 got clone 생성한 repository :$ git clone https://github.com/komdoory/webpublisher_komdoory.git / (결과) Administrator@G501-13 MINGW64 /c/KOMDOORY_Work/webpublisher_komdoory (master) : Git과 연결되었다는 의미 확인

4. README.md 파일을 생성 및 내용 작성 : $touch로 타이포라 파일 하나 만들어주고 내용 입력하고

   (결과) $ cat README.md : (캣아이) 저장되었나 확인함

5. push/pull 이전에 계정을 연결 (아래 택배순서)

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

7. github의 자료를 pull (가져오기) 처리하여 가져오기

---

## 택배보내는순서

1. 물건을 포장한다 : 파일을 만든다
2. 상자에 담는다 : $ git status로 확인 -> $git add 파일이름

1. 우체국에 간다

2. 송장 작성 (내용설명: commit)

   :$ git commit -m (썸머리의 m) "생성을위한첫파일"(예시) : 내용설명

3. 물건 보내기 : $ git push -> git 로그인창 뜸

   이제 동기화 되었음

