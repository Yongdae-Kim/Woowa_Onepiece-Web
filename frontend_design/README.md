# 웹페이지를 어떻게 만들 것인가?

<https://gomockingbird.com/projects/gqwna3w/4gXVnC>

<https://gomockingbird.com/projects/gqwna3w/TnMd3U>

---

Q) 메인화면 전체 디자인 방향은?

A) 눈에 잘 들어오는 플랫 디자인을 사용하면 좋을 것 같음

<http://engineering.buzzni.com/2015/03/02/why-flat-design-now.html>

<http://cimple.postype.com/post/746/>

---

Q) 메인화면의 광고 이미지에 대한 애니메이션 효과는?

A) 좌우로 슬라이드 되면 좋을 것 같음

<http://photoswipe.com/>

<http://www.sitepoint.com/5-jquery-touch-swipe-image-gallery-plugins/>

---

Q) 지도 API 는 어떤것을 사용 할 것인가?

A) 제주도 지도의 경우 Daum API 가 보다 잘 정리되어 있음

<http://m.blog.naver.com/wowterry/110183552787>

---

Q) 사이드 바의 나타나는 광고의 기준은 무엇인가?

A) 선택 된 정류장을 바탕으로 주변 광고들을 보여줄 것, 디폴트 값으로 특정 정류장을 보여줌

---

Q) 스크롤 할때 몇개의 데이터를 불러 올 것인가?

A) 스크롤 시 10 ~ 15 개 정도의 데이터만 쿼리를 통해 우선 가지고 올 것

---

Q) 이미지의 버벅거리는 문제 해결은?

A) 캐시 또는 Lazy Loading 을 통하여 해결

<http://fhopeman.github.io/justlazy/>

---

Q) 지도의 좌표를 어떻게 나타낼것인가?

A) 지도 API 에 따르면 경위도 값으로 좌표를 이동 시킬 수 있음, 버스정류장의 경위도 값은 구글맵의 GET 파라미터로 구할 수 있음

---

Q) 검색어 입력 후 액션은?

A) 검색어 입력 후 자동완성을 목록을 보여줄수 있도록 함, Jquery-Autocomplete 사용

<https://www.devbridge.com/sourcery/components/jquery-autocomplete/>

---

Q) 타입별 광고를 어떻게 보여 줄 것인가?

A) 타입별로 마커를 다르게 해서 보다 눈에 잘 보일 수 있도록 함, 체크박스를 두고 선택을 통하여 원하는 타입 별 광고를 볼 수 있도록 함

---

Q) 광고 상세 보기에 대한 모달창은?

A) vex 모달 라이브러리 사용

<http://github.hubspot.com/vex/docs/welcome/>

---

Q) 사이드 광고의 이동에 따라 지도위 마커 이동

A) 광고를 선택 할 경우, 광고의 경위도를 바탕으로 마커의 좌표를 이동시킴

---

Q) 정류소에서 버스노선 선택 시 출발시간을 보여주는 방법은?

A) 텍스트 애니메이션 효과를 쓰면 좋을 것 같음

<https://jschr.github.io/textillate/>

---

## 그 밖에 우려되는 문제점

1. 마커가 많아짐에 따라 버벅거리는 문제가 있지않을까?

2. 사용자 클릭 이벤트에 맞춰서 부드럽게 마커가 이동할 수 있을까?

3. 광고 데이터가 많아짐에 따라 사이드 바의 데이터를 늘려야 하지 않을까?

4. 과연 어떤 지도 API 를 선택하는게 맞는 것일까?
