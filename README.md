# DeviceMarket

## 프로젝트 소개
JSP/Servlet 기반으로 구현한 휴대폰 쇼핑몰 웹 서비스입니다.  
상품과 옵션(색상, 용량)을 분리하여 실제 쇼핑몰 형태의 기능을 구현했습니다.

## 주요 기능
- 상품 등록 / 수정 / 삭제
- 상품 목록 및 상세 조회
- 옵션 선택 (색상, 용량)
- 옵션별 가격 및 재고 관리

## 기술 스택
- Java, JSP/Servlet
- Oracle DB, JDBC
- HTML, CSS, JavaScript, AJAX
- Apache Tomcat

## 구조
MVC(Model2) 패턴 기반  
Controller - DAO - DTO 계층 분리

## 핵심 구현
상품과 옵션을 분리 설계하여  
하나의 상품에 여러 옵션을 유연하게 관리할 수 있도록 구현
