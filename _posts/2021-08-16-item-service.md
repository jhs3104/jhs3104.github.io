---
layout: post
---

# 상품 관리 서비스
core, servlet, springmvc 프로젝트를 통해 학습한 내용을 바탕으로 구현한 간단한 상품관리(상품 등록, 목록 조회, 상품 수정) 서비스

## Description

Spring MVC

- Spring MVC 패턴 적용하여 상품 컨트롤러 및 뷰 구현

서비스 제공 흐름 구현

- 상품 목록 -> 등록 및 저장 -> 상품 상세  
- 상품 목록 -> 상품 상세 -> 상품 수정 -> 상품 상세

View 페이지 구현 

- Bootstrap
- Thymeleaf

HTTP Method로 기능 구분

- ex)GET: 상품 등록 폼, POST: 상품 등록

PRG 패턴 적용

- Post - Redirect - GET
- Redirect를 하지 않으면 상품 등록 후 새로 고침시 중복 등록

AWS로 배포

- AWS EC2 인스턴스로 프로젝트 배포
- 비용 문제로 인하여 12:00 ~ 18:00 배포



## Images

![item_list](./images/item_list.png)[^1]

![item_add](./images/item_add.png)[^2]

![item_details](./images/item_details.png)[^3]

![PRG](./images/PRG.png)[^4]

---
{: data-content="footnotes"}

[^1]: 상품 목록 화면
[^2]: 상품 등록 폼 
[^3]: 저장 완료 화면
[^4]:   상품 서비스 동작 방식. PRG 패턴 적용
