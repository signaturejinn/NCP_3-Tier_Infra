## NCP_3-Tier_Infra 구축
### NCP 서비스를 활용한 3-Tier 웹서비스 인프라 구축

</br>

## 🗓️ 진행 기간
- 2022.08.24 ~ 2022.08.26

</br>

## 👥 팀 구성
- Infra 구축 2명

</br>

## ⚙️ 사용 기술
#### CSP
<img src="https://img.shields.io/badge/Naver NCP-03C75A?style=for-the-badge&logo=Naver&logoColor=white"> <!--NCP-->

#### OS
<img src="https://img.shields.io/badge/CentOS-262577?style=for-the-badge&logo=CentOS&logoColor=white"> <!--CentOS-->

#### DB
<img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white">  <!--mysql-->

#### Team Collabolation Tool
<img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white"> <!--Notion-->

#### Architecture Draw Tool
<img src="https://img.shields.io/badge/Drawio-000000?style=for-the-badge&logo=Drawio&logoColor=white"> <!--Draw.io-->

</br>


## 🙋🏻‍♂️ 담당 업무
- VPC 구성
- Block Storage 생성 후 마운트
- Web Server 인스턴스 생성 및 Apache 설치
- Was Server 인스턴스 생성 및 Apache Tomcat 설치
    - Web Was Server 연동
    - DB 구성 및 연동

</br>

## 📝 상세 내용 
### 📌 Infra Architecture
![image](https://user-images.githubusercontent.com/117608997/216755229-52b7b5d7-86cd-42a4-9923-d1d30c20763e.png)
```
Web 서버 구축
- Block Storage 마운트 후 Apache 8.44 설치

Was 서버 구축
- Block Storage 마운트 후 Apache Tomcat 8.5.82 설치

Web-WAS 연동
- mod_proxy

Was-DB 연동
- jdbc
```

</br>

## ⛓️ 구축 과정
### 🔗 Notion Link
#### - [NCP Project](https://glen-party-257.notion.site/NCP-b08ecfc37232433f9acca9105e682b3f)
</br>
