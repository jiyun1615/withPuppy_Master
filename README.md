
# 강아지와

> 반려견 관련 종합 컨텐츠

강아지 커뮤니티부터 쇼핑몰, 관련 다양한 서비스까지 한눈에 제공되는 사이트입니다. 
## notion
https://electric-hat-2a3.notion.site/8beb79dc8c9a4817885614ba245c9e2b?pvs=4

## 프로젝트개요
![프로젝트개요](https://github.com/Starrain96/withPuppy_Master/assets/124110590/570cb47f-4152-43a9-bcdb-1544cf34258d)

## 메뉴구성도
![메뉴구성도](https://github.com/Starrain96/withPuppy_Master/assets/124110590/6384e2e5-65b3-4466-82ac-97d04d62d016)

## 전체 순서도
![전체순서도](https://github.com/Starrain96/withPuppy_Master/assets/124110590/a574f767-53ff-4835-854e-1118c347a047)

## ERD
![ERD](https://github.com/Starrain96/withPuppy_Master/assets/124110590/e0ebb260-e554-4839-8532-cf882dd04f5a)

## 주요 기능

### 커뮤니티
- 전체게시판, 자유게시판, 수도권, 지방
  - 게시판 형태의 crud ...


### 쇼핑몰
- 카테고리별 상품 조회 페이지 : 카테고리에 따른 상품 분류, 페이지네이션, 정렬기준 변경
- 상품상세 페이지 : 상품에 대한 상세 정보, 수량 선택 및 장바구니 담기
- 장바구니 페이지 : 상품 삭제, 수량 변경, 장바구니 총액 표시, 결제하기 페이지로 이동
- 주문 확인서 페이지 : 주문 정보, 주문자 정보 입력, 결제 API 연동
    - transaction 처리를 통해, 재고 수량 부족의 경우 exception, 재고 감소 및 품절처리
- 관리자 상품관리 페이지 : 상품 검색, 정렬 조회, 상품 정보 수정, 상품 등록, 상품 삭제 기능
- 관리자 매출 통계 페이지 : 매출 현황 정보, 카테고리별 매출 그래프, 기간별 매출 조회
- 
![1](https://github.com/jiyun1615/withPuppy_Master/assets/51588209/c8e8041b-adfa-4d46-acf1-f00efc3ac4d7)
![2](https://github.com/jiyun1615/withPuppy_Master/assets/51588209/5f5b2461-a2e2-4a9c-8dfa-7d2b503a270a)
![4](https://github.com/jiyun1615/withPuppy_Master/assets/51588209/635d1c05-32d4-4081-8b98-4e7eb7df5ce0)
![5](https://github.com/jiyun1615/withPuppy_Master/assets/51588209/c18d7049-5ebb-4925-9495-0d84e5817f6f)
![6](https://github.com/jiyun1615/withPuppy_Master/assets/51588209/030bdc7a-138b-4320-a762-93b4fff7f409)
![7](https://github.com/jiyun1615/withPuppy_Master/assets/51588209/74953788-a50b-48d2-a9dd-e8c1b3dfafb1)
![8](https://github.com/jiyun1615/withPuppy_Master/assets/51588209/838ccfc4-7403-4e22-9ce6-6d2167b88836)
![9](https://github.com/jiyun1615/withPuppy_Master/assets/51588209/25b5b305-a6d6-48b6-b0df-56e19d3d916e)
![10](https://github.com/jiyun1615/withPuppy_Master/assets/51588209/5a4840da-cf92-4432-b0b6-ce7f9cab832f)


### 동물병원
- 동물병원 찾기 페이지, 본인 위치 기반 근처 5개의 병원 리스트업, 검색
- 상세 동물병원 페이지, 병원 기본 정보, 위치 표시(카카오맵API), 후기 점수 및 내용 리스트업
- 후기 작성하기 페이지, 후기 작성 및 영수증 이미지 첨부 시 OCR API 호출하여 영수증 JSON 데이터 추출 후 입력
- 진료비 페이지, 추출한 영수증 데이터로 자료 표준화, 지역 별 검색 가능(본인 위치기반 검색이 기본), 항목 별 검색
  
![동물병원-1](https://github.com/Starrain96/withPuppy_Master/assets/124110590/b5e6e98b-74bf-4a32-909f-e03ed6295fbd)
![동물병원-2](https://github.com/Starrain96/withPuppy_Master/assets/124110590/a141a7c4-915b-434f-8efd-9616e4d71c77)
![동물병원-3](https://github.com/Starrain96/withPuppy_Master/assets/124110590/938a367e-14ce-4c97-b9e8-335198917cb3)
![동물병원-4](https://github.com/Starrain96/withPuppy_Master/assets/124110590/38d16ee7-81a6-4482-8a31-fea64a2c0663)
![동물병원-5](https://github.com/Starrain96/withPuppy_Master/assets/124110590/401c2af6-0b7d-44a7-9d96-f82795da784e)
![동물병원-6](https://github.com/Starrain96/withPuppy_Master/assets/124110590/6076f9ce-38a4-452b-b4b7-ae4f081aebbc)
![동물병원-7](https://github.com/Starrain96/withPuppy_Master/assets/124110590/0992c00a-65e0-4d40-b2a2-8dcae33c941d)
![동물병원-8](https://github.com/Starrain96/withPuppy_Master/assets/124110590/c0e3a1a5-26d0-44ae-a503-f31eeb10c749)

## 구현 예정 사항
![구현예정사항](https://github.com/Starrain96/withPuppy_Master/assets/124110590/4367c06d-c85c-4c0c-b1c0-9a3c6da761c3)
