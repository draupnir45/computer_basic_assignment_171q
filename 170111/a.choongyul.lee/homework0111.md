﻿#### ActiveX가 무엇일까?  / 국내 웹에 ActiveX가 정착된 된 이유 및 배경

ActiveX는 사용자의 PC에 설치해 여러 종류의 파일과 데이터들을 웹에서 보여줄 수 있도록 하는 마이크로소프트의 플러그인 기술이다.
'마이크로소프트'의 플러그인 기술인 만큼 윈도우즈 플래폼에서만 작동한다. 

국내 웹에 ActiveX가 정착된 배경에는 공인인증서의 개발에 맞물린 면이 가장 큰데, 정부가 전자인증서를 통한 본인인증을 법으로 의무화 시켰고 
그 본인인증이 당시 웹 환경의 SSL(Secure Sockets Layer, 인터넷에서 정보를 암호화해서 송수신하는 프로토콜)은 56비트 암호키만 이용할 수 있었고 
이는 당시 사용중이던 다른 암호화 방식보다 상대적으로 허술한 방식이었기 때문에 독자적인 암호화 방식을 만들었는데 그 방식이 
ActiveX 이었고 자연스럽게 한국의 웹 개발자들은 모든 웹사이트와 인터넷 프로그램을 마이크로소프트에서 지원하는 환경에 맞춰 출시하기 시작했다.
일반인들은 공인인증서의 사용을 위해 IE를 사용해야했고 IE를 서비스하면서 필요한 파일들을 ActiveX 환경으로 배포하기 시작하여 걷잡을 수 없이 뻗어나갔다. 


#### 기술적 부채(Technical Debt)
빠르게 기술력을 개발하기 위해 포기하는 것들이 결국에는 부채로 차후에 돌아온다는 것이다.<br/>
빨리 해결되지 않으면 실제 빚의 특징처럼 점점 더 커진다는 것.

예를들면 제품에서 발생된 작은 이슈를 무시하고 출시한 자동차가 차후 리콜되는 것을 생각해 볼 수 있을것 같다.

기술적인 문제를 해결하기 위해서는 시간과 돈이 필요한데 시간 전쟁과 같은 스타트업 시장에서는 
빨리 고객에게 선보일 제품을 만들어내고 시장에 진입하는 것도 중요할수 있다.
때문에 반드시 나쁘다고만 할수는 없지만 위에서 조사한 ActiveX에 대입해 보면 이 기술적 부채를 빚으로 인식조차 하고있지 못할 경우 얼마나 큰 짐이 돌아오는지 생각해 볼만 하다. 

문제점이 누적되어 어디서부터 손대야 할지 모르는 수준에 다다르면 유지보수가 아니라 재구축을 해야하는 상황이 벌어지기 때문에 기술적 부채 또한 갚을수 있을때 차근차근 갚아 나가는게 현명하다는 생각이 든다.



#### 위 내용을 조사하며 느낀 점

처음에는 ActiveX와 기술적 부채에 대해 정확히 몰라서 이후에 학습하는 내용에 관련해서 두가지를 조사해 오는 것으로 생각했었는데
ActiveX가 미친 한국사회의 악영향을 사회학적으로 설명할때 기술적 부채라는 용어를 사용할수 있을 것 같다.

오늘 걷지않으면 내일은 뛰어야한다. 같은 말이 있다.
우리나라의 본인인증 환경이 특정 환경에 머물러 있을 때, 당시는 몰랐지만 지금에 와서 얼마나 우리가 뛰어야 할지 조차 모르는 상황이 되었다는게 안타까웠다.
주로 이 내용에 대해 기술하고 있는 사람들이 추후 우리나라의 본인인증 환경이 더 나아질 거라고 생각하지 않았고 
그 이유가 기술에 대해 잘 알지못하는 사람들이 일부 현상만 놓고 탁상공론을 하고있다고 이야기하는 것을 보며 나에 대해 되돌아보게된다.


우리가 공부하는데 있어서도 지금은 배우는 입장이므로 빠르게 개발(간단하게는 코딩결과)을 하기위해 놓치는 개념이 있을 경우 추후에 어떻게 돌아올지 모르기 때문에 
매일매일 학습내용도 잘 정리해 나가야 할 것 같다는 생각이 든다.

오늘의 짐이 3개월 뒤에 부채가 되지않도록.