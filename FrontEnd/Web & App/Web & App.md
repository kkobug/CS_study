# Web & App 인데 거의 App

<img src="https://velog.velcdn.com/images/nogomin/post/53a9df84-636c-4939-a2b3-61f276e1fe1d/native-hybrid-webapp.PNG" alt="post-thumbnail" style="zoom: 67%;" />

### 웹(Web)

World Wide Web의 줄임말로 WWW라고 부르기도 합니다.

웹에는 수많은 웹사이트들이 있고 각각의 웹사이트는 웹 페이지라는 것으로 이루어집니다.

웹 페이지를 점으로 찍고 링크로 서로 연결된 웹 페이지들을 선으로 이으면 다음의 그림과 같이 표현됩니다.

![ê±°ë¯¸ì¤ ê°ì ì¹](https://www.betterweb.or.kr/wp-content/uploads/2013/12/Screenshot-from-2013-12-30-165448.png)

온라인상에 다양한 정보가 서로 연결되어 있는 것을 **웹**이라고 하며 

인터넷에서 흔히 사용되는 크롬, 사파리, 엣지 등은 웹 브라우저라고 합니다. 



### 반응형 웹 (Responsive Web)

하나의 웹에서 PC, 스마트폰, 대블릿PC 등 접속하는 디스플레이의 크기에 따라 자동으로 변하는 웹

하나의 웹사이트를 만들어 다양한 디바이스에 대응할 수 있습니다.





## 앱

### 네이티브 앱 ( Native App) 

흔히 말하는 스마트폰 **앱**, 애플리케이션을 말하며, 모바일기기에 최적화 되어 있습니다.

**안드로이드** SDK를 이용해 Java언어로 만든 앱과  **IOS** 기반 SDK를 이용해 Swift로 제작이 가능

스토어를 통해서 다운로드하고 해당 OS(Android, IOS)에서만 구동이 가능합니다.

스마트폰에 저장된 고유 정보나 카메라등의 하드웨어 제어 기능을 사용 할 수 있습니다.

※[SDK]는 SOFTWARE DEVELOPMENT KIT 의 약자로 소프트웨어를 개발하는 도구

![image-20220628200310476](C:\Users\PARK\AppData\Roaming\Typora\typora-user-images\image-20220628200310476.png)

장점

웹 앱, 하이브리드 앱과 비교했을때 성능이 가장 좋습니다.

네이티브 API를 호출하여 사용함으로 플랫폼과 밀착되어 있습니다.



단점

네이티브 앱을 개발하고 유지보수하는 것은 상당히 길고 복잡한 과정

상당한 비용이 소요되는 경우도 많습니다.

해당 플랫폼 별로 다른 언어를 사용함으로 각각의 언어를 알고 있어야합니다.



### 웹 앱 ( Web App)

모바일 화면에 맞게 개발된 웹 페이지

스토어를 통한 설치가 **불가능**  ,   웹브라우저를 통해서 접속이 가능

<img src="C:\Users\PARK\AppData\Roaming\Typora\typora-user-images\image-20220628200251822.png" alt="image-20220628200251822"  />

장점

따로 설치할 필요가 없습니다.

모든 기기와 브라우저에서 접근할 수 있습니다.

유지보수가 용이 합니다.(설치 및 승인 과정이 필요없음)



단점

스마트폰의 기능을 사용할 수 없다는 단점이 있습니다. (ex 카메라 QR코드 등)

네이티브 , 하이브리드 앱보다 실행이 까다롭습니다. (브라우저를 열고 검색해 들어가야 함)



### 하이브리드 앱 ( Hybrid App )

하이브리드 앱은 기본적으로 ' 네이티브앱 + 웹앱 ' 이라고 생각하시면 쉽습니다. 

일반적으론 네이티브웹에 웹view를 띄워 웹앱을 실행 시키는 것이 보편적이며 양쪽의 API 를 모두 사용할 수 있는것이 큰 장점 입니다.

<img src="C:\Users\PARK\AppData\Roaming\Typora\typora-user-images\image-20220628200217262.png" alt="image-20220628200217262"  />

장점

네이티브 API 와 브라우저 API 를 이용한 다양한 개발이 가능 합니다.

웹개발 기술을 사용해 앱을 개발할 수 있습니다.

한번의 개발로 다수의 플랫폼에 대응할 수 있습니다.



단점

네이티브 기능에 접근하기 위해선 네이티브 개발 지식이 필요합니다.

웹뷰에서 앱을 실행하는 경우이기 때문에 앱의 성능이 곧 브라우저의 성능입니다.

UI 프레임워크 도구를 사용하지 않는다면 개발자가 UI를 제작해야 합니다.



### 프로그레시브 웹 앱 (progressive web app)

웹과 네이티브 앱의 기능 모두의 이점을 갖도록 수 많은 특정 기술과 표준 패턴을 사용해 개발된 웹 앱입니다.

HTML, CSS, 자바스크립트(JavaScript)와 같은 웹 기술로 만드는 앱



장점

네이티브 앱을 개발하는 것은 상당히 어렵지만, PWA는 훨씬 더 빠르게 개발할 수 있다는 것

푸시 알림이나 오프라인 지원과 같은 네이티브 앱의 특징들도 전부 제공



단점

네이티브 앱에 비해서 지연 속도가 크고 배터리 소모량이 더 많습니다. 

 iOS 기능이 완벽하게 동작하지 않습니다.





### 결론

어떤 앱? 웹을 개발하는게 가장 좋은가요?



일반 사용자에게 똑같은 앱으로 보이지만 서비스를 하는 회사 입장에서는 고려할 부분들이 많기 때문에 앱의 종류와 구분이 필요



네이티브 앱은 기능이 좋고 안정적이지만 안드로이드와 iOS에서 서비스하기 위해 개발 비용과 유지 비용, 기간, 관리 등의 문제가 있고

하이브리드 앱은 기간도 적게 걸리고 비용도 네이티브 앱에 비해 저렴하지만 유저들을 사로잡을 만한 퍼포먼스를 구현하기 어려움



초기에는 많은 기능들이 필요 없고, 유저들의 니즈나 프로토타입 정도로 사용할 목적

예산도 아낄 겸 가격도 저렴하고 기간도 짧은**웹앱** 또는 **하이브리드 앱**을 고민



추후 사용자 니즈가 많아지거나 유저 수가 급증하면 **네이티브 앱**을 고민







출처: 

https://record-than-remember.tistory.com/entry/ 웹, 웹앱, 하이브리드 앱, 네이티브 앱의 차이점

https://m.blog.naver.com/acornedu/221012420292   [모바일] 네이티브앱 vs 모바일웹앱 vs 하이브리드앱

[PWA(Progressive Web App) 특징 및 장단점](https://blog.naver.com/ghkdalki456/222397308483)