![IAB Tech Lab](https://drive.google.com/uc?id=10yoBoG5uRETSXRrnJPUDuONujvADrSG1)


# **AdCOM 1.0**

#### 개요

IAB 표준 중 가장 성공적인 사례 중 하나는 OpenRTB다. 이 프로토콜은 판매 측 익스체인지와 수요 측 입찰자 간의 실시간 경매를 위한 것으로, 2011년 2월 OpenRTB v1.0 Mobile로 처음 출시되었다. 같은 해 OpenRTB v2.0이 출시되면서 모바일, 디스플레이, 비디오를 통합한 프로토콜을 제공했다. 업계 전반에 걸친 채택으로 OpenRTB는 2012년 1월 v2.1 버전 출시와 함께 IAB 표준으로 자리 잡았지만, 기술 내용에 대한 관리는 여전히 OpenRTB 커뮤니티가 담당했다. 이후 초기 목표에 충실하게 OpenRTB는 실시간 프로그램 광고의 공통 언어가 되었으며, 2018년 v2.5 버전으로 진화했다.

이 기간 동안 프로그램 광고는 업계에서 주도적인 역할을 해왔다. 그러나 이로 인해 공급망이 점점 더 복잡해지면서 사기율과 기타 위험 요소가 증가하는 문제가 발생했다. 이는 OpenRTB v3.0을 추진하는 주요 동기 중 하나다. 현재와 미래의 프로그램 광고 문제를 해결하기 위해 필요한 수준의 변화는 하위 호환성을 유지하는 방식(즉, 추가적인 v2.x 버전 출시)으로는 달성할 수 없었기 때문이다.

OpenMedia의 목표인 IAB 표준 포트폴리오 합리화와 결합되어, OpenRTB는 실제 미디어 거래(예: 경매 파라미터, 딜, 입찰 등)에 초점을 맞추고, 다른 사양과 공통된 개념(예: 광고, 배치, 사용자, 기기, 사이트, 퍼블리셔 등)은 재사용 가능한 별도의 사양으로 분리하는 계층적 접근 방식을 채택했다. 이렇게 해서 Advertising Common Object Model, 줄여서 AdCOM이 탄생했다.

AdCOM은 OpenRTB 외에도 다른 사양에 모듈성을 제공함으로써 프로그램 광고의 비즈니스 과제를 해결하려고 한다. 예를 들어, 퍼블리셔는 전통적인 디스플레이 광고가 불투명한 방식으로 전달되기 때문에 자신의 자산에서 실행되는 크리에이티브 유형을 제어할 수 있는 능력이 제한적이다. 과도한 페이로드, 브랜드 안전성 부족, 과도한 픽셀 발사, 악성코드를 실행하는 자바스크립트와 같은 바람직하지 않은 크리에이티브가 퍼블리셔 콘텐츠에 유입되는 경우가 많다.

이와 같은 문제 행동은 사용자 경험을 저하시키고 잠재적으로 손상을 초래하며, 사용자 신뢰를 떨어뜨리고, 광고 차단기 설치를 유발하며, 퍼블리셔의 수익 창출을 약화시키고, 광고주 측의 선의의 행위자가 의도한 대상에 도달하기 어렵게 만든다. AdCOM은 이러한 문제를 해결하기 위해 새로운 안전한 구조화된 광고 형식을 지원한다.

여러 IAB 사양에서 AdCOM을 재사용함으로써, 이와 같은 솔루션을 다양한 업계 애플리케이션에 걸쳐 활용할 수 있다.


#### 이 저장소에 대해

이 저장소의 **master** 브랜치는 항상 AdCOM의 최신 릴리스를 포함한다. 최신 사양은 master 브랜치의 ["AdCOM v1.0 Final.md"](https://github.com/InteractiveAdvertisingBureau/AdCOM/blob/master/AdCOM%20v1.0%20FINAL.md) 파일에서 확인할 수 있다.

이전 릴리스에 대한 브랜치도 존재한다. 이 브랜치들을 사용해 한 릴리스에서 다른 릴리스로의 상세 변경 사항을 검토할 수 있다. 간단한 변경 로그는 사양 문서 내부에서 확인할 수 있다.

**develop** 브랜치는 다음 릴리스를 위한 작업 중인 내용을 포함한다. 이 브랜치는 언제든지 변경될 수 있다.


#### OpenMedia

https://iabtechlab.com/openmedia


#### OpenRTB

https://github.com/InteractiveAdvertisingBureau/openrtb


#### 문의

추가 정보나 참여를 원하시면 openmedia@iabtechlab.com으로 이메일을 보내주세요.


#### IAB Tech Lab 소개

IAB Technology Laboratory(Tech Lab)는 효과적이고 지속 가능한 글로벌 디지털 미디어 생태계의 성장을 촉진하기 위해 표준, 소프트웨어, 서비스를 개발하고 제공하는 비영리 연구 개발 컨소시엄이다. 디지털 퍼블리셔와 광고 기술 회사, 마케터, 에이전시, 인터랙티브 마케팅 분야에 관심이 있는 기업들로 구성된 IAB Tech Lab은 투명하고 안전하며 효과적인 공급망, 더 간단하고 일관된 측정, 소비자를 위한 더 나은 광고 경험을 통해 브랜드와 미디어의 성장을 가능하게 하는 것을 목표로 한다. 특히 모바일과 TV/디지털 비디오 채널 활성화에 중점을 둔다. IAB Tech Lab의 포트폴리오에는 소비자, 퍼블리셔, 광고주, 제3자 플랫폼을 위한 디지털 경험을 개선하기 위해 설계된 DigiTrust 실시간 표준화된 신원 서비스가 포함된다. 이사회 멤버로는 AppNexus, ExtremeReach, Google, GroupM, Hearst Digital Media, Integral Ad Science, Index Exchange, LinkedIn, MediaMath, Microsoft, Moat, Pandora, PubMatic, Quantcast, Telaria, The Trade Desk, Yahoo! Japan 등이 있다. 2014년에 설립된 IAB Tech Lab은 뉴욕시에 본사를 두고 있으며 샌프란시스코에 사무실을, 시애틀과 런던에 대표부를 두고 있다.

IAB Tech Lab에 대해 더 알아보기: [https://www.iabtechlab.com/](https://www.iabtechlab.com/)


#### 기여자 및 기술 거버넌스

OpenRTB 작업 그룹 멤버들이 이 저장소에 기여한다. OpenRTB 작업 그룹에 참여하려면 IAB Tech Lab의 멤버여야 한다. 프로젝트의 기술 거버넌스와 코드 커밋은 IAB Tech Lab OpenRTB 커밋 그룹이 담당한다.


### 라이선스

OpenRTB 스펙은 IAB Tech Lab이 Creative Commons Attribution 3.0 라이선스 하에 제공된다. 이 라이선스의 사본을 보려면 creativecommons.org/licenses/by/3.0/을 방문하거나 Creative Commons, 171 Second Street, Suite 300, San Francisco, CA 94105, USA로 문의한다.

AdCOM 저장소, Programmatic Supply Chain Working Group의 구성원, 또는 AdCOM과 관련된 IAB Tech Lab에 아이디어, 스펙, 소프트웨어 코드, 문서, 파일 또는 기타 자료(각각 "제출물")를 제출함으로써, 여러분은 해당 제출물을 Creative Commons Attribution 3.0 라이선스 하에 IAB Tech Lab에 라이선스 부여하는 데 동의한다. 또한 해당 제출물이 이 라이선스의 조건에 따라 공개적으로 사용 및 제공될 수 있음을 인정한다. 만약 여러분이 IAB Tech Lab의 구성원이라면, [IPR 정책](https://iabtechlab.com/ipr-iab-techlab/acknowledge-ipr/)의 조건 또한 여러분의 제출물에 적용될 수 있다. IPR 정책이 제출물에 적용되는 경우, Creative Commons Attribution 3.0 라이선스와 IPR 정책 간의 충돌이 발생할 때는 IPR 정책이 우선한다.


#### 책임의 한계

여기서 제공되거나 사용되는 표준, 사양, 측정 가이드라인 및 기타 자료 또는 서비스("제품 및 서비스")는 "있는 그대로" 및 "이용 가능한 상태로" 제공된다. IAB 테크놀로지 랩러토리, Inc.("테크 랩")은 이와 관련하여 어떠한 보증도 하지 않으며, 명시적, 묵시적 또는 법적 보증을 포함한 모든 종류의 보증을 부인한다. 이에는 상품성, 특정 목적에의 적합성, 이용 가능성, 오류 없음 또는 중단 없는 운영에 대한 보증, 그리고 거래 관행, 수행 과정 또는 상관습에서 비롯된 모든 보증이 포함되지만 이에 국한되지 않는다. 테크 랩이 적용 가능한 법률에 따라 묵시적 보증을 부인할 수 없는 경우, 그러한 보증의 범위와 기간은 해당 법률에서 허용하는 최소한으로 제한된다. 

제품 및 서비스는 비즈니스 또는 법적 조언으로 간주되지 않는다. 테크 랩은 여기서 제공되거나 사용되는 제품 및 서비스가 귀하 및/또는 귀하의 제품 또는 서비스가 모든 적용 가능한 법률, 규정 또는 자율 규제 프레임워크를 준수하도록 할 것이라고 보증하지 않는다. 귀하는 데이터 보호 법률을 포함하되 이에 국한되지 않는 모든 법적 요구 사항을 준수할 책임이 있으며, 이에는 캐나다의 개인정보 보호 및 전자문서법, EU 데이터 보호 지침, EU 전자 프라이버시 지침, EU 일반 데이터 보호 규정(GDPR), 그리고 발효 시 EU 전자 프라이버시 규정 등이 포함된다.


