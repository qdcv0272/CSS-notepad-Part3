# Css 속성 알아보기 Part1

___
## 박스 모델
1. width, height
2. span
3. div
4. max,min
5. 단위
6. margin
7. padding
8. border
9. overflow
___

### width, height
요소의 가로 / 세로 너비를 지정할수가 있습니다.<br/>
auto : 브라우저가 너비를 계산
___
### span
인라인 요소!<br/>
auto: 포함한 콘텐츠 크기만큼 자동으로 줄어듬<br/>
![스크린샷 2022-03-10 오후 7 32 08](https://user-images.githubusercontent.com/91595135/157643622-ef50d830-d31a-4e59-823d-336ef3463a34.png)

___
### div
블럭 요소!<br/>
auto: width는 부모 요소만큼 크기가 자동으로 늘어나고 height 는 콘텐츠 크기만큼 자동으로 줄어듬<br/>
![스크린샷 2022-03-10 오후 7 32 59](https://user-images.githubusercontent.com/91595135/157643761-90bf0ff3-0659-4ccf-ac1f-ab4785928c47.png)
___
### max,min
max-width, max-height: 요소가 커질수 있는 쵀대 가로 / 세로 너비<br/>
min-width, min-height: 요소가 작이질 수 있는 최소 가로 / 세로 너비
___
### 단위
px: 픽셀 <br/>
%: 백분율 <br/>
em: 글꼴 크기 <br/>
rem: 루트 요소 의 글꼴 크기<br/>
vw: 뷰포트 가로 너비 백분율 <br/>
vh: 뷰포트 세로 너비의 백분율 <br/>
___
### margin
요소의 외부 여백 을 지정하는 단축 속성<br/>
![스크린샷 2022-03-10 오후 7 40 15](https://user-images.githubusercontent.com/91595135/157644953-56e26ab6-542c-4c61-8685-a60fa7ad3ed8.png)![스크린샷 2022-03-10 오후 7 42 08](https://user-images.githubusercontent.com/91595135/157645260-2ae75ef4-82df-4549-82ad-b82a684ebaf3.png)

___
### padding
요소의 내부 여백 을 지정하는 단축 속성 (요소의 크기가 커짐!)<br/>
사용 방법은 margin이랑 똑같다.<br/>![스크린샷 2022-03-10 오후 7 42 27](https://user-images.githubusercontent.com/91595135/157645320-b0f0bb95-7084-4024-b0ca-67448aab7d22.png)
___
### border
요소의 테두리 선을 지정하는 단축 속성
# border: 선-두께 선-종류 선-색상;
### border-radius : 요소의 단위만큼 모서리를 둥글게 깎음
___
### overflow
요소의 크기 이상으로 내용이 넘쳤을 때, 보여짐을 제어하는 단축 속성
___
