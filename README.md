# sample rxswift beginning

rxswift 공부하자!
> RX : **R**eactive E**x**tensions
리엑티브 프로그래밍 패러다임이고 데이터 흐름과 그 데이터의 변경에 따라 전달 되는 것을 중
요시 생각하는 패러다임 같습니다. 엑셀과 비슷하다고 합니다. 

>> 그리고 rxswift 이니.. 
Functional + RX = Functional Reactive Programming(FRP)을 해야겠죠...
>> 아래에 FRP의 구현체가 있습니다. 그것으로 셈플링할 것입니다.

<pre>
ReactiveX
rxswift 셈플링을 하며 기능 익히기를 위한 레파지토리입니다. 
</pre>

# 좋은 링크
- FRP의 구현체 : http://reactivex.io/
- http://www.rxmarbles.com/

# 좋은 블러그
- https://magi82.github.io/ios-rxswift-01/

# 어떻게 시작을 해야될까?
<pre>
어떻게 시작을 어떻게 해야될지 모르겠습니다. 
어떤 라이브러리를 기본으로 가져가서 프로젝트를 생성하며, 
그걸 기반으로 기본 UI를 해보고, 
네트워크 활용을 해보면 기초적인 개념은 익힐 것 것 같아서 .. 
이런 순서로 기본 기능들을 사용해 나가면 되지 않을 까 싶습니다. 
</pre>

# 사용할 라이브러리
## 코어
- [RxSwift](https://github.com/ReactiveX/RxSwift) : 스위프트 버전의 RX

## 네트워크
- [RxAlamofire](https://github.com/RxSwiftCommunity/RxAlamofire) : Swift Alamofire를 RxSwift로 감싼 HTTP 네트워킹 라이브러리


# 기본 용어
## Observable
- 비동기적으로 다수의 이벤트를 다루는 방법입니다.
- 옵저버 패턴의 확장이라 생각하면 됩니다.
- 추가로 콜드 옵저버블 의 개념이 더 추가 되어 있습니다. : 누군가 자신을 구독해야 Lazy evaluation(느긋한 계산법)이 되서 이벤트를 발생시키는 개념의 추가


# 실전
.. 구독하자 구독하자...... 
천천히 하자 ~~
