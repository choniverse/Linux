리눅스 웹 환경 ; AWS Cloud9

1. CLI Command Line Interface < 리눅스는 이거
 <-> GUI Graphic User Interface
 
2. 내리는 명령은 현재 머물러 있는 Directory를 대상으로 이루어진다
 - 현재 디렉토리 확인 방법 ; pwd ; Print Working Directory
 - 현재의 하위에 폴더 추가하기 ; mkdir [이름] ; make directory -> ls로 확인
 - 현재 하위에 파일 추가하기 ; touch [파일명.확장자]

 - dir과 file 확인하는 방법엔 ls가 있는데 이는 dir과 file 구분이 안 됨
  -> ls -l 입력하면 따로 나옴 ; list
  -> 이렇게 마이너스 뒤에 나오는 걸 파라미터, 매개변수라고 함 
    -> 앞에 d가 붙어있으면 dir이라는 뜻
    
 - 현재 dir 바꾸기 ; cd ; chand directory
 - 상위 dir로 돌아가기
    1. 절대 경로 ; cd home/ec2-user/environment/
    2. 상대 경로 ; cd .. ; 현재 디렉토리의 부모 디렉토리로 이동

+ clear ; 화면 깨끗하게

 - 파일 삭제 ; rm [파일명]
 - 폴더 삭제 ; rm -r [dir이름] ; -r은 안에 있는 것도 다 삭제됨 (재귀적)
 - 명령어 확인 ; rm --help
