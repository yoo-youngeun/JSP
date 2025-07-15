# 📘 JSP Study Repository

**학습 내용:** JSP, JSTL, Session 등을 활용한 웹 애플리케이션 구현

## 🛠️ 학습 스택 및 주제

- **JSP (JavaServer Pages)**  
  - 기본 문법, 디렉티브, 암시적 객체 활용  
- **JSTL (JSP Standard Tag Library)**  
  - `<c:out>`, `<c:set>`, `<c:forEach>`, `<c:if>`, `<c:choose>` 등 Core 태그 사용 학습 :contentReference[oaicite:2]{index=2}  
- **EL (Expression Language)**  
  - `${sessionScope.name}`, `${param.xxx}` 등의 표현식 사용 :contentReference[oaicite:3]{index=3}  
- **Session 관리**  
  - `session.setAttribute()` → JSP/JSTL 및 서블릿에서 조회 :contentReference[oaicite:4]{index=4}

---

## 🧩 주요 기능 정리

- **Session 활용 예제**  
  - 로그인 플로우, 사용자 정보 저장 및 화면 표시
- **JSTL을 통한 조건문 및 반복 출력 구현**  
  - 메뉴 구성 항목 등 동적 바인딩
- **EL 태그를 통한 변수 출력 및 조건 제어**  

---

## 📝 실습 파일 구조  
├── src/  
│ ├── index.jsp // 메인 페이지 예제  
│ ├── sessionExample.jsp // Session 읽기/쓰기 실습   
│ ├── jstlExample.jsp // JSTL <c:forEach>, <c:if> 예제   
│ └── web.xml // 서블릿 매핑 및 설정   
└── lib/   
└── jstl-1.2.jar // JSTL 라이브러리 파일    
---

## ⚙️ 실행 환경 설정

1. Tomcat (v9 이상) 설치  
2. `lib/jstl-1.2.jar` 파일을 `WEB-INF/lib/` 디렉터리에 넣기  
3. 프로젝트 전체를 Tomcat `webapps/` 경로에 배포  
4. 브라우저에서 `http://localhost:8080/프로젝트명/index.jsp` 실행
