# git repository


저장소 | 설명
---|---
bare repository    | 원격 저장소, 작업 이력, 변경 사항들 존재
nonbare repository | 로컬 저장소, 작업 트리, 실제 작업 파일 존재  



## bare repository
: 여러 클라이언트가 공유하는 저장소   


```bash
# 서버에 베어 저장소 생성
[계정@서버주소] $ mkdir 디렉토리.git
[계정@서버주소] $ cd 디렉토리.git
[계정@서버주소 디렉토리]$ git init --bare
```



## nonbare repository


**방법**  
- 생성 - 기존 디렉터리를 저장소로 사용
- 복제 - 서버에 존재하는 저장소를 복제해 사용


```bash
# 로컬 저장소 생성
## .git 디렉토리가 생성되며 저장소에 필요한 뼈대 파일 존재  
$ git init


# 원격 저장소 복제
$ git clone 주소
$ git cloen 계정@서버주소:경로/디렉토리.git
```



[top](#)
