## oo 프로젝트 Front-end/Back-end 소개

- 식재료 시장에 새로운 가치를 부여한다  [정육각](https://www.jeongyookgak.com/brandstory) 클론 프로젝트
- 개발은 초기 세팅부터 직접 구현!

### 개발 인원 및 기간

- 개발기간 : 2021/7/5 ~ 2021/7/16
- 개발 인원 : 프론트엔드 3명, 백엔드 3명
- [백엔드 github 링크]()

### 프로젝트 선정이유

- 리액트를 2주동안 배우고 props, state, 컴포넌트 재사용 등에 익숙해지기 위해 깔끔하고 간결한 사이트를 선정하였습니다.

### 데모 영상(이미지 클릭)

*유투브 영상 링크나 캡쳐 이미지 넣어주세요.*

<br>

## 적용 기술 및 구현 기능

### 적용 기술

> - Front-End : React.js, sass, 
> - Back-End : Python, Django web framework, Beautifulsoup, Selenium, Bcrypt, My SQL
> - Tool : slack, AWS(EC2,RDS), git


### 구현 기능

#### 공통 (이재현)


- 일반 회원가입 / 로그인

- navbar
메인페이지 - 슬라이드

네비바 - 로그인여부를 확인해서 로그인버튼 안보이게


#### 메인페이지 (이재현)

- 추천 상품, 오늘의 상품, 베스트 상품 모두 각각 api 호출하여 구현
- 저쩌구


#### 리스트페이지  (박관용)

-카테고리 filtering / sorting ( 동적 라우팅을 통해 각각의 카테고리별 아이템, 아이템 순서 정리)
-item 컴포넌트  구현 ( main,list 컴포넌트에서 재사용)
-장바구니 modal창 구현 ( main,list 컴포넌트 재사용 )

-카테고리 클릭 시 query 파라미터를 활용하여 새로고침 후에도 selected 유지

-메인 페이지와 리스트페이지에서 상품 클릭 시 각각의 상세페이지로 이동( 동적 라우팅 사용)


#### 상세페이지  (장운서)

- 상품의 정보들 props로 모두 받아옴

- 상품의 수량변경

- 상품 button option 이 아닌 button  으로 구현

- 상품의 정보 담아서 장바구니로 post  해줌

- 상품이 장바구니에 담길때 keyfram 모션 활용

- 상품의 정보와 상품의 리뷰를 토글로 of&off 구현

- 상품이 장바구니에 담기고 나서 setTimeOut으로 모션이 지나간 후 장바구니 페이지로 이동

리뷰 : 
상품 리뷰를 토큰을 받아와서 페이지에 뿌려줌

상품 리뷰 삭제 기능 추가




#### 마이페이지  (박관용)

- 쿠폰 , 주문이력 백엔드와 통신
- 로그아웃 시 localStorage에서 삭제시키는 정도로 구현
- 카테고리별 회원 정보 뿌려주기 (동적 라우팅)
- 신선배송 가능 지역을 가진 회원의 경우 신선배송 태그 보여주기.


#### 장바구니 (이재현)
- 수량 변경 : 
창고? 재고량을 초과하지 않도록 구현.

장바구니에 넣어둔 상품이 0개가 됬을 경우. 품절이라고 표시

품절인 상품이 있는데 구매하려들 경우 알람창 표시하고 삭제를 유도


#### 신선배송  (박관용)

- 카카오 주소 api 사용 ( 신선배송 가능 지역 백엔드와 통신 통해 가능 여부 판별)





<br>

*아래 Reference 부분은 README.md에 꼭 포함되어야 하는 내용입니다*

## Reference

- 이 프로젝트는 [정육각](https://www.jeongyookgak.com/) 사이트를 참조하여 학습목적으로 만들었습니다.
- 실무수준의 프로젝트이지만 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다.
- 이 프로젝트에서 사용하고 있는 사진 대부분은 위코드에서 구매한 것이므로 해당 프로젝트 외부인이 사용할 수 없습니다.
