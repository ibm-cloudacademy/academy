# Apache Tomcat Examples for Cloud Native Post Academy Deep Dive

개발자 확습 코스에 온것을 환영합니다.

이 예제는 현재 사용하고 있는 Web Application을 클라우드 Native Application을 전환하는 것을
학습하는 과정입니다.

현 시스템을 Cloud TA(Transformation Advisor)를 도구를 이용하여 전환작업을 수행하며
아래의 과정으로 클라우드 Native Application Developer가 필요로 하는 역량을 경험하고자 합니다.

  * Transformation Advisor 및 리포팅 정보 활용
  * Application 오류 수정
  * Build war 
  * 현 Application 을 컨테이너화
  * 현 Application 클라우드 컨테이너 플랫폼의 IKS 환경에 배포

이번 학습코스는 아래와 같은 과정을 수행합니다. TA 리포팅정보를 기반으로
오류를 해결하여 IKS에 배포하십시요

![alt text](img/ta_runtime_trans.png)


## Docker Base Image
```
FROM websphere-liberty
```

## git 에서 소스를 받아서 sts에 import 하십시요

![alt text](img/01_import_academy.png)

![alt text](img/02_existing_project.png)

![alt text](img/03_import_project.png)

![alt text](img/04_select_zip.png)

![alt text](img/05_import_finish.png)

![alt text](img/06_import_complete.png)




