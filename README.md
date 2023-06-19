# e-commerce Architecture

## D2C

### Headless Commerce

[Headless 정의](https://macharchitecture.com/
- The user experience (what the customer sees) is decoupled from the back-end services, allowing businesses to deliver solutions to a variety of devices in a multi-channel environment, in a cost-effective and efficient manner.
-  Headless systems are API-First services that allow the creation of applications where the user experience is completely decoupled form the back-end.
- Instead of offering a traditional user interface (presentation layer), headless systems make its content accessible via RESTful or GraphQL APIs that can be consumed by many type of services.
- 

## 국내 현황 
[국내 MACH관련 - 2023.05.10](https://news.nate.com/view/20230510n24882)

- NHN커머스가 자사몰(D2C) 구축 솔루션 '샵바이'를 통해 글로벌 이커머스 솔루션 산업에서 대두되고 있는 키워드인 '마크(MACH)'를 제시했다.
- 10일 NHN커머스에 따르면 회사의 '샵바이'가 1인 창업자부터 중대형 쇼핑 기업들까지 각 비즈니스에 최적화된 확장형 이커머스 플랫폼 라인업을 완성했다. 회사는 호스팅 업체 '고도몰'을 운영하며 쌓은 노하우를 바탕으로 '샵바이'를 서비스하고 있다. 샵바이는 클라우드 환경에서의 편리한 서비스 확장과 집중되는 트래픽에 유연하게 대응할 수 있는 시스템인 점이 특징이다. 글로벌 이커머스 솔루션 산업에서 대두되고 있는 최신 IT 기술인 MACH 기술을 도입했다.
- 마크는 △Microservices based(마이크로서비스 아키텍쳐) △API-first(API 중심 디자인) △Cloud-native SaaS(클라우드 네이티브 SaaS) △Headless(헤드리스)의 앞글자를 땄다. 이용자들은 △간편 로그인·배송 서비스·라이브 커머스 등 쇼핑몰 운영을 위한 앱을 원클릭으로 적용할 수 있는 앱스토어 기능 △여러개 쇼핑몰 통합 관리가 가능한 멀티프론트 기능 △무제한 연동이 가능한 250여개의 오픈 API 등 더 업그레이드된 기능을 이용할 수 있다. 이를 통해 대형 마켓플레이스, 프랜차이즈 형태의 쇼핑몰 구축이 용이하게 됐다. 실제 소니스토어, SK티딜, 아프리카TV, 보이스캐디 등이 샵바이 솔루션을 통해 자사 쇼핑몰을 구축했다.
- SK티딜은 SK텔레콤 고객 대상의 인공지능(AI) 큐레이션 문자 쇼핑 서비스로, 샵바이의 헤드리스 커머스 방식을 높이 샀다. 헤드리스 커머스는 고객 접점이 되는 채널(프론트엔드)과 기능을 제공하는 서비스(백엔드)를 분리한 시스템을 말한다. 마치 레고 블록을 조립하듯이 백엔드의 데이터를 다양한 프론트엔드로 확장, 변경할 수 있는 기술이다. 티딜이 SK텔레콤 고객 전용 쇼핑 서비스인 만큼 인증 절차가 필요한데, 회원 연동 API를 활용해 회원 통합도 쉽게 가능했음을 강조했다.
- NHN커머스에 따르면 하반기에도 KT딜, 대원미디어 등 다양한 중대형 D2C 쇼핑몰이 샵바이를 통해 오픈될 예정이다. NHN커머스 관계자는 "샵바이는 1인 기업부터 중대형 비즈니스까지 쉽게 D2C 쇼핑몰을 구축할 수 있는 대표 쇼핑몰 솔루션"이라며 "올 상반기 내 약 300여개 이상 앱을 추가로 제공해 이용자 맞춤형 쇼핑몰 구축을 적극 지원할 계획"이라고 전했다.

[쇼핑몰 솔루션 3사, 엇갈린 운명 속 승자는?](http://www.weeklypost.kr/news/articleView.html?idxno=2564)
- 통상 온라인 판매자들은 스마트스토어에서 자신의 회사를 키워 자사몰로 독립하기를 원했다. 스마트스토어는 네이버의 정책을 철저히 따라야 하므로 제약사항도 많고, 스킨이나 기능 측면에서도 부족함이 많기에 발생한 현상이다. 결정적으로 고객의 개인정보를 취득할 수 없고, 다양한 마케팅도 펼칠 수 없다는 뚜렷한 한계가 명확하다. 네이버는 자사 내부 서비스에 외부 스크립트를 삽입하는 것을 원천적으로 허용하지 않고 있다. 구글 및 페이스북과 가장 큰 차이점 중 하나다. 이 때문에 인스타그램은 스마트스토어 연동을 약관 변경까지 해가며 아예 금지했다. 네이버는 열어주지 않으면서 정작 스마트스토어는 인스타그램을 이용해 돈을 벌고 있으니 괘씸하다고 여길 법도 하다.
- 카페24나 네이버나 전자상거래 플랫폼을 내세우지만, 실질적인 수익은 광고를 통해 발생한다는 점에 주목할 수 있다. 네이버 42만 스마트스토어 중 월 1억 원을 넘기는 업체는 약 4,000개 정도에 달한다. 이들 스토어가 월 100만 원만 쇼핑 광고를 집행해도 넉넉잡아 4,200억 원의 안정된 고정 수익이 발생한다.


[커머스 기업들이 쓸 수 밖에 없는 서비스를 만듭니다](http://www.weeklypost.kr/news/articleView.html?idxno=2564)


## Reference

[NHN COMMERCE shop by](https://www.nhn-commerce.com/z/shopby/intro?bn=GNB_shopby)
