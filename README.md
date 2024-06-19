# <div align=center>Simmongs</div>

<div align=center>명지전문대학 인터넷보안공학과 캡스톤디자인 생산관리 ERP 웹 사이트</div>

<br>

## 🖥️ 프로젝트 소개

![Simmongs_pipeline 002](https://github.com/parkuijin/SimmongsBackend/assets/45947824/e4be26c7-16d9-4172-982a-ff4bce90b995)

<br>

## 🔨 프로젝트 구조

![Simmongs_pipeline 001](https://github.com/parkuijin/SimmongsBackend/assets/45947824/cb62d442-fc14-44dc-9215-f12ee6c863f0)

![Simmongs_pipeline 004](https://github.com/parkuijin/SimmongsBackend/assets/45947824/e7c4ce8f-bf5e-4070-b77e-7883e0d43328)

![Simmongs_pipeline 005 001](https://github.com/parkuijin/SimmongsBackend/assets/45947824/f19e5f2a-4f8f-470b-b15c-5b0d9d1126d8)

<br>

<br>

## 📌 주요 기능

### [ 재고 관리 ]

#### 1. 재고 등록
`POST` `/products/uploadProduct`
<br>

#### 2. 재고 조회
`GET` `/products/showAll`
<br>

#### 3. 재고 수정
`POST` `/products/updateProduct`
<br>

#### 4. 재고 삭제
`DELETE` `/products/deleteProduct`
<br>

#### 5. 재고 검색
`POST` `/products/searchProducts`
<br>

<br>

### [ BOM ]

#### 1. BOM 등록
`POST` `/bom/registration`
<br>

#### 2. BOM 조회
`GET` `/bom/showAll`
<br>

#### 3. BOM 삭제
`DELETE` `/bom/delete`
<br>

<br>

### [ 작업 지시 ]

#### 1. 작업 지시 등록
`POST` `/workorder/registration`
<br>

#### 2. 작업 지시 조회
`GET` `/workorder/showAll`
<br>

#### 3. 작업 지시 중단
`POST` `/workorder/stopWorkOrder`
<br>

#### 4. 작업 지시 검색
`POST` `/workorder/searchWorkOrder`
<br>

<br>

### [ 작업 실적 ]

#### 1. 작업 실적 등록
`POST` `/workperformance/registration`
<br>

#### 2. 작업 실적 검색
`POST` `/workperformance/showWorkPerformance`
<br>

#### 3. 작업 실적 삭제
`DELETE` `/workperformance/delete`
<br>

<br>

### [ 입출고 ]

#### 1. 입출고 등록
`POST` `/storingunstoring/registration`
<br>

#### 2. 입출고 조회
`GET` `/storingunstoring/showAll`
<br>

#### 3. 입출고 검색
`POST` `/storingunstoring/searchStoringUnstoring`
<br>

<br>
