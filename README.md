# PEER_3조
## 목차
- [요구사항 분석](#요구사항-분석)

- [프로젝트 개발 환경](#프로젝트-개발-환경)

- [버전](#버전)

- [협업툴](#협업툴)

- [담당 역할](#담당-역할)

- [구현한 자료들](#구현한-자료들)

## 요구사항 분석
![요구사항_분석](https://user-images.githubusercontent.com/96768840/207750792-86aff260-811f-41ea-ab4d-2b036c976782.jpg)

## 프로젝트 개발 환경
- *SpringBoot*
- *Gradle*
- *Bootstrap*
- *Tomcat*
- *Oracle*
- *AWS*
- *Thymeleaf*
- *JavaScript*
- *jQuery*
- *HTML5&CSS3*

## 버전
- *SpringBoot 2.7.5 ver.*
- *STS 3.9.11*
- *Gradle (Buildship 3.x)*
- *Java 11 ver.*
- *Oracle 11c.*
- *Apache Tomcat 9.0 ver.*
- *OJDBC8*
- *Bootstrap 5.x*
- ***그 외 Gradle Dependency 사용***

## 협업툴
<details>
    <summary>1. 깃허브</summary> 
 
![깃허브](https://user-images.githubusercontent.com/96768840/207810035-fdb5b923-e760-45e6-9a21-4e5e7b5690e3.jpg)
![깃허브1](https://user-images.githubusercontent.com/96768840/207810039-0d08a343-e58c-44d3-bb22-cf87e7a6f057.jpg)

</details>

<details>
    <summary>2. 노션</summary> 
<img width="882" alt="image" src="https://user-images.githubusercontent.com/96768840/207756457-3bfeac4d-559e-4377-bc9c-dd117b734e97.png">

![이슈](https://user-images.githubusercontent.com/96768840/207810903-0e31df72-bb73-4fa6-9ea8-a61f0daf9f71.jpg)
![브레인스토밍](https://user-images.githubusercontent.com/96768840/207810908-97111dbb-2fc3-44a9-bcb1-d7d0b637ca1c.jpg)

</details>

## 담당 역할
### CSS 총괄 및 관리
<details>
    <summary>메인 페이지(DatePicker, 검색 기능)</summary>
    
![메인](https://user-images.githubusercontent.com/96768840/207751292-1291fcc8-37d3-4a1f-bf7d-3ba8e4d0867f.jpg)

</details> 

<details>
    <summary>검색 페이지(지도(카카오 맵 API) 구현 / 숙소 목록)</summary> 
    
![검색결과_지도](https://user-images.githubusercontent.com/96768840/207751276-537b907c-a894-4d27-bb89-4956525302f5.jpg)
![검색결과_목록](https://user-images.githubusercontent.com/96768840/207751278-b8e368e7-e7e2-44c0-80f4-5046bf11dd47.jpg)
    
</details> 


## 구현한 코드 목록
### [PEER/src/main/java/peer/controller/main/MainController.java](PEER/src/main/java/peer/controller/main/MainController.java)
### [PEER/src/main/java/peer/dao/main/MainMapper.java ](PEER/src/main/java/peer/dao/main/MainMapper.java )
### [PEER/src/main/java/peer/model/main/MainBean.java](PEER/src/main/java/peer/model/main/MainBean.java)
### [PEER/src/main/java/peer/service/main/MainService.java](PEER/src/main/java/peer/service/main/MainService.java)
### [PEER/src/main/java/peer/service/main/MainServiceImpl.java](PEER/src/main/java/peer/service/main/MainServiceImpl.java)
### [PEER/src/main/resources/static/css](PEER/src/main/resources/static/css)
### [PEER/src/main/resources/static/mapper/Main.xml](PEER/src/main/resources/static/mapper/Main.xml)
### [PEER/src/main/resources/templates/main.html](PEER/src/main/resources/templates/main.html)
### [PEER/src/main/resources/templates/search.html](PEER/src/main/resources/templates/search.html)
