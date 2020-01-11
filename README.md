# VCS
Version Control System     
= SCM (Source Code Management)   
: 버전 관리 시스템   
: 소스 코드를 포함한 파일의 변경 사항-버전 관리        
: 파일을 이전 상태로 되돌리거나 삭제된 파일 복구 가능      
: 협업시 파일을 분기해 작업을 분리하고 완료되면 파일 결합       


**유형**
- Local VCS
- Centralized VCS
    - CVS
    - Subversion
    - Perforce
- Distributed
    - Git
    - Mercurial
    - Veracity
    - Bazaar



## Centralized VCS
: 중앙 집중식 버전 관리 시스템  
: client-server 모델 기반 파일 관리     
: 중앙-서버에 파일이 존재하고 이를 클라이언트가 받아 사용하고 변경 사항을 중앙에 반영         
: 파일의 변경 사항을 중앙에서 관리해 클라이언트가 모든 변경 사항을 파악할 수 있음    


**종류**
- CVS
- Subversion
- Perforce



## Distributed VCS  
: 분산 버전 관리 시스템      
: peer-to-peer 모델 기반 파일 관리     
: 파일을 개별 클라이언트가 로컬 사본으로 관리하고 변경 사항을 통합할 준비가 되면 중앙에 요청하여 마스터 사본으로 병합      
: 파일이 로컬에서 관리되므로 네트워크 연결 문제 보완   


**종류**  
- Git
- Mercurial
- Veracity
- Bazaar
