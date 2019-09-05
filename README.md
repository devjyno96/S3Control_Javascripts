S3Control_Javascripts
=========================

#함수명 이름 약속

>기능적용단위+   
>ex)
>createBoard
>listBoard

#필요 함수 목록

>###createBorad
>>게시판 생성 - 최상위 폴더 생성

>###listBoard
>>폴더 목록 조회 함수 만들기

>###viewBorad
>>...
>>
>###uploadObject
>>업로드 키값은 sha1 시간 포함한 넘버링
>>
>###viewObject
>>...
>>
>###downloadObject
>>테스트 안해봄 해봐야됨
>>
>###listObject
>>폴더 내부의 폴더, 파일 리스트 보여주기, 파일와 폴더 구분은 어떻게 하지?
>>
>##구현해야할 함수
>>
>###searchBorad
>>...
>###searchObject
>>...


#화면 순서

>1. index   
>>버튼을 통해 listBoard 실행    
>2. 게시판 목록 listBoard.html  
>>listBoard, createBoard 실행   
>3. 게시판 생성 화면 createBoard.html   
>>createBoard 실행 후 그 게시판 내부 화면(viewBoard 화면 실행)
>4. 게시판 내부 화면 viewBoard.html   
>>viewBoard, 파일 클릭 시 게시판 내부 파일화면(viewObject)실행
>5. 파일 화면 viewObject.html   
>>viewObject, downloadObject 실행   
>6. 파일 업로드 화면 uploadObject.html   
>>uploadObject 실행
