---
description: 'null'
keywords: 디버거;experience cloud debugger extension;chrome;extension;release notes
seo-description: 'null'
seo-title: 릴리스 노트
title: 릴리스 노트
uuid: 47a5d6f3-c074-4ad5-ad4b-e6030496689b
translation-type: tm+mt
source-git-commit: 3fd50cde86f0dfc5f66d8faf63112adf24beeac0

---


# 릴리스 노트{#release-notes}

## 릴리스 노트 {#topic-a92c3eb799b74e7fa404af8af5efb215}

## Version 0.0.817 May 17, 2019 {#topic-5dc9026cac864330b04361b1da8309a8}

## 새로운 기능 {#section-71352536e6894ad08f307535529394cd}

<table id="table_7EFCAF456B14404FAF3715FC56519AAF"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 기능 </th> 
   <th colname="col2" class="entry"> 설명 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>사후 처리 히트 데이터 </p> </td> 
   <td colname="col2"> <p> 처리 규칙이 실행된 <a href="solutions.md#section-f71dfcc22bb44c86bec328491606a482" format="dita" scope="local"></a>후 Analytics 히트에 대한 값을 보는 기능을 추가했습니다. </p> </td> 
  </tr> 
 </tbody> 
</table>

## 버전 0.0.810 2019년 3월 6일 {#topic-83bb7ddd68594177be9fd7826b650b80}

## 새로운 기능 {#section-0a2f6fcb0045464fa11f0586c69f7ffd}

<table id="table_96AEBFF29F3D40CAA859133B22756B0C"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 기능 </th> 
   <th colname="col2" class="entry"> 설명 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>감사 테스트 </p> </td> 
   <td colname="col2"> <p> 디버거에 <a href="run-debugger.md#section-82bc57440406461ebf27a16855b71655" format="dita" scope="local"> 감사 테스트</a> 추가 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Adobe Audience Manager </p> </td> 
   <td colname="col2"> <p>이제 디버거가 AAM 응답을 표시합니다. </p> </td> 
  </tr> 
 </tbody> 
</table>

## 버그 수정 {#section-f5e9d54e9d2546afb97972cdb6d8a093}

* 바닥글이 페이지 하단에 컨텐츠를 숨기는 문제가 해결되었습니다.

* 디버거 바닥글 업데이트
* Target에 오래된 용어가 사용된 문제가 해결되었습니다.

## 버전 0.0.809 2019년 2월 28일 {#topic-6241de45fa9e4a23a95ad4d3a73f7348}

## 새로운 기능 {#section-14036b9f2c0144fdac5e292ea42ce564}

<table id="table_66E255E9BA8845CAA92779F580D14EB4"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 기능 </th> 
   <th colname="col2" class="entry"> 설명 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>포함 코드 함수 </p> </td> 
   <td colname="col2"> <p> 바꾸기 및 포함 코드 함수 삽입 </p> </td> 
  </tr> 
 </tbody> 
</table>

## 개선 사항 {#section-e9e8a6ddedde4c029b1d3d69c009cbad}

* 문서의 기밀 정보 가리기 때문에 발생할 수 있는 취약성 문제가 해결되었습니다.

## 버그 수정 {#section-556417ff055848c1bf037354dd43cbd0}

* AAM 탭에서 AAM DIL 이벤트가 캡처되지 않는 문제가 해결되었습니다.

* 동적 삽입 시작 시 사용자 인터페이스가 다른 포함 코드에 매핑되는 문제가 해결되었습니다.
* 잘못된 URL이 계속 표시되는 동적 삽입 론치의 문제를 해결했습니다.
* 디버거 창을 닫아도 디버거가 포함 코드를 계속 바꾸는 문제가 해결되었습니다.

## 버전 0.0.806 2018년 9월 10일 {#topic-a41c9d1969ff4d06ac3bb4e7d6b6d18a}

## 새로운 기능 {#section-4eb2a6ed26a44abc96623384a7e94b0f}

<table id="table_9AC6DE90AF4345DFA707BFBA1E58C328"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 기능 </th> 
   <th colname="col2" class="entry"> 설명 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>도구 탭의 분석 링크 </p> </td> 
   <td colname="col2"> <p>IMS 로그인을 통해 Analytics API를 통해 evar/prop에 대한 친숙한 이름을 표시합니다. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>동적으로 시작 삽입 </p> </td> 
   <td colname="col2"> <p>도구 탭에서 페이지에 Launch를 동적으로 삽입하여 Launch가 설치되어 있지 않은 페이지에 대해 테스트할 수 있습니다. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>타겟 개선 사항 </p> </td> 
   <td colname="col2"> <p> 
     <ul id="ul_5FCD61733462495D8FB421DE7C813001"> 
      <li id="li_2E8E9AAE5D0D41DC8C42592AFDFA3377">Target 요청에 대한 성능 시간이 추가되었습니다. </li> 
      <li id="li_98A56E71D72542D694A76DF84CE26AFA">adobe.target.trackEvent 캡처 </li> 
     </ul> </p> </td> 
  </tr> 
 </tbody> 
</table>

## 개선 사항 {#section-56003a12c32f4998bf1cf2a25a518592}

* 테이블 높이가 너무 크지 않도록 네트워크 탭 표시를 개선하여 사용자가 가로로 스크롤하기 전에 세로로 스크롤되도록 했습니다. 이전에는 스크롤 막대가 표 하단에 표시됩니다. 표의 크기가 상당히 커지므로 사용자는 표를 보려면 세로로 스크롤해야 합니다.
* 도구 탭에서 ObservePoint로 연결되는 링크를 업데이트했습니다.

## 버그 수정 {#section-d9231f5c77254d0888347e5f569a8b1d}

* Experience Cloud 탭이 업데이트되지 않는 문제가 해결되었습니다.

* 현재 "Advertising Cloud" 이름이 아닌 네트워크 탭의 솔루션 행에 "Media Optimizer"가 표시되는 문제가 해결되었습니다.
* 디버거가 모든 페이지에 _satellite를 삽입하는 문제를 해결했습니다.

## 버전 0.0.803 2018년 8월 10일 {#topic-d2901fb70ce04a5586f6c7a994fce875}

버전 0.0.803에는 고객 대면 변경 사항이 포함되어 있지 않습니다.

## 버전 0.0.802 2018년 8월 1일 {#topic-b93cd396af5e49dc97cd86264871aeb4}

## 새로운 기능 {#section-e6699fb9c9b24035ace56d6a84c9d09b}

<table id="table_E847A9D6711F4CF59E98806FA7AF8379"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 기능 </th> 
   <th colname="col2" class="entry"> 설명 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>도구 탭의 감사 링크 </p> </td> 
   <td colname="col2"> <p>디버거에서 Auditor에 대한 링크를 추가했습니다. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>축소 탭 </p> </td> 
   <td colname="col2"> <p>축소된 탭은 요약 및 도구 탭에 유지됩니다 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>클릭하여 보기 </p> </td> 
   <td colname="col2"> <p> 모든 탭에 클릭유도문안 기능 추가 </p> </td> 
  </tr> 
 </tbody> 
</table>

## 개선 사항 {#section-0e7090e3e6a645f085d4553b983ecff8}

* Media Optimizer의 이름을 Advertising Cloud로 변경
* 네트워크 탭에서 솔루션을 제거했습니다.

## 버그 수정 {#section-7c0e4cc4b00a428489bed4a0a27c9501}

* "셀 클릭하여 보기" 기능이 업데이트되지 않는 문제가 해결되었습니다.
* AAM 탭에 AAM 히트가 표시되지 않는 문제를 해결했습니다.

## 버전 0.0.798 2018년 6월 14일 {#topic-3b2d44277f2f4c0295d82724c34bf467}

## 새로운 기능 {#section-0d73ae8b7ced417e9039f986fafaa102}

<table id="table_8FDED5A7B7F7430A88AE441336F9C714"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 기능 </th> 
   <th colname="col2" class="entry"> 설명 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Excel 내보내기 옵션 </p> </td> 
   <td colname="col2"> <p>네트워크 탭에 Excel 내보내기 옵션이 추가되었습니다. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>향상된 모양 </p> </td> 
   <td colname="col2"> <p>Chrome 확장 글꼴을 Adobe Clean으로 업데이트했습니다. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> 트랙패드 스와이프 기능 </p> </td> 
   <td colname="col2"> <p>앞으로/뒤로 트랙패드 스와이프 기능이 비활성화되었습니다. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>원시 서버 호출 표시기 </p> </td> 
   <td colname="col2"> <p>원시 서버 호출 문자열이 복사되었다는 표시기가 추가되었습니다. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>로그 정리 탭 </p> </td> 
   <td colname="col2"> <p> 
     <ul id="ul_D1EB0BE3A01C494983DAAF625562AC62"> 
      <li id="li_2696D26320F54A089D3CC99962EC9670">해당 솔루션에 대한 라인 항목이 로그에 없으면 솔루션 필터에서 솔루션 숨기기 </li> 
      <li id="li_D4586A6AB2AD42BB9F0FA3E7A01382C6">DTM에만 적용되므로 DTM 호출을 찾을 수 없는 경우 수준 필터 숨기기 </li> 
      <li id="li_E2AF179037DC4C63B960013AB1F9AD6A">[수준] 열에 표시된 아이콘을 변경하면 </li> 
      <li id="li_3DB6682D6C9040D99F04C688E208CE1F">DTM 라인 항목에 대한 "코드 표시" 서식 표준화 </li> 
     </ul> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>바닥글의 도움말 링크 업데이트 </p> </td> 
   <td colname="col2"> <p>바닥글의 도움말 링크를 https://marketing.adobe.com/resources/help/en_US/experience-cloud-debugger/으로 <a href="https://marketing.adobe.com/resources/help/en_US/experience-cloud-debugger/" format="https" scope="external"> 업데이트</a> </p> </td> 
  </tr> 
 </tbody> 
</table>

## 버그 수정 {#section-c292cf7dcb17463bb1928de73bd55121}

* 배지 번호가 지워지지 않는 문제가 해결되었습니다.
* 고객이 빈 요약 정보를 보고했던 문제를 수정했습니다.

## Version 0.0.797 May 25, 2018 {#topic-51490f4f42aa40eb879663fad9d62916}

## 새로운 기능 {#section-bbf8ff7e000e4b5592d348e0870471f6}

<table id="table_8CF872DC245A46C38FE21490C842D47A"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 기능 </th> 
   <th colname="col2" class="entry"> 설명 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Mbox 전환 </p> </td> 
   <td colname="col2"> <p>Mbox 전환은 타겟 탭에 추가되었습니다. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>필터 설정이 고정 </p> </td> 
   <td colname="col2"> <p>이제 필터 설정이 네트워크의 화면 상단과 로그 탭에 고정됩니다. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>네트워크 값 보기 및 복사 </p> </td> 
   <td colname="col2"> <p>네트워크 탭에서 세부 사항을 보고 셀의 값을 복사할 수 있습니다. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>법적 바닥글 링크 및 저작권 </p> </td> 
   <td colname="col2"> <p>합법적인 바닥글 링크 및 저작권 정보를 사용자 인터페이스에 추가했습니다. </p> </td> 
  </tr> 
 </tbody> 
</table>
