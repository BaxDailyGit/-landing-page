# landing-page

포트폴리오 랜딩 페이지를 제작하였습니다.  
본 랜딩 페이지는 저의 간단한 소개, 경험했던 프로젝트, map, email을 제공합니다.  
  
GitHub Pages를 통해 호스팅되며, 다음 링크를 통해 확인할 수 있습니다: [Portfolio Landing Page](https://baxdailygit.github.io/landing-page/pages/)  
활동 기록은 [Blog](https://baxdailygit.github.io/categories/#landing-page)에 올려두었으니 참고바랍니다!



### 포트폴리오-랜딩페이지 완성화면 캡쳐
![screencapture-baxdailygit-github-io-landing-page-pages-2024-01-25-16_20_50](https://github.com/BaxDailyGit/landing-page/assets/99312529/6c3cbdf3-ecf4-4f08-96c3-ef7a9cb067d8)



------------------

## 0. 랜딩 페이지를 제작하기 앞서

소프트웨어공학에서는 소프트웨어 개발을 계획하고 관리하기 위한 개발방법론이 있습니다. 

이번에 개인 프로젝트를 진행하기 앞서  방법론까지는 아니더라도 체계적으로 계획하고 관리, 기록하며 개발해보고자 단계를 정하고 이것에 맞추어서 진행하려고 합니다.


1. **`목표 설정`**
2. **`기술 스택 및 컨벤션 구성`**
3. **`프로젝트 초기화`**
4. **`디자인 및 레이아웃 계획`**
5. **`컴포넌트 개발`**
6. **`API 연동`**
7. **`테스트`**
8. **`배포`**

------------------



## 1. 목표 설정

> * 진행했던 개발 프로젝트를 소개하는 포트폴리오 랜딩 페이지를 만듭니다.
> * 라이브러리를 사용하지 않고 순수한 HTML, CSS, JavaScript만을 사용합니다.
> * 더미 이미지api와 지도api를 활용하여 제작합니다. 

단순히 웹 페이지를 출력하는 랜딩 페이지를 제작하는것이 목적이 아닌 개발 후 지속적으로 유지보수할 계획이 있습니다. 

또한 JavaScript를 익히고자 남는 공간에 api를 활용하고자 합니다.

------------------

### 1.1 요구사항 수립

하나씩 퀘스트 깨는 느낌으로 요구사항을 리스트로 적어보았습니다.

#### 요구사항

* 프로젝트 목록
* 프로젝트 상세 정보
* 연락처 정보
* 이력서 다운로드
* 사는 지역을 나타내는 지도
* 스크롤 애니메이션
* 반응형 디자인

------------------

## 2. 도구 및 기술 스택 구성


* 웹 페이지의 구조와 스타일을 정의 : **`HTML/CSS`**   
* 상호작용, 이벤트 처리, AJAX 통신 : **`JavaScript`**   
* 로컬 개발 서버(테스트) : **`Live Server`**
* 개발 환경(IDE) : **`IntelliJ`**
* 버전 관리 : **`git / github`**

------------------

### Branch
 branch 의 종류 중 main, develop, feature 이 3가지 브랜치를 사용해 프로젝트를 나눌 생각입니다. 

> * main branch  
> 최종 완성본을 담고 있는 브랜치 
> * develop branch  
> 전체 개발 작업이 진행되는 브랜치 
> * feature branch  
> 특정 기능이나 작업을 개발할 별도의 브랜치 

흐름은 다음과 같습니다.
![image](https://github.com/BaxDailyGit/BaxDailyGit/assets/99312529/eed5b21e-ceb4-460e-9ae9-f8bb9927ce60)

------------------

### 커밋 컨벤션

개발도중 커밋을 보면 이것을 왜 만들었는지 모를때가 있습니다. 그래서 아래와 규칙을 정해 변경사항을 빠르고 쉽게 파악하려고 합니다. 


**`Feat`** : 새로운 기능을 추가하는 경우  
**`Design`** : CSS 등 사용자가 UI 디자인을 변경했을 때  
**`Style`** : 코드 포맷 변경, 세미콜론 누락, 코드 수정이 없는경우  
**`Comment`**	: 필요한 주석 추가 및 변경
**`Fix`** : 버그를 고친경우  
**`Refactor`** : 코드 리펙토링  
**`Test`** : 테스트 코드. 리펙토링 테스트 코드를 추가했을 때  
**`Rename`** : 파일명(or 폴더명) 을 수정한 경우  
**`Remove`** : 코드(파일) 의 삭제가 있을 때  
**`Docs`** : 문서를 수정한 경우
