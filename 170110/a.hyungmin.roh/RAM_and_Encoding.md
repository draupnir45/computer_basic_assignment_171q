##RAM == Random Access Memory :zap:
읽고쓰는 속도가 매우 빠른 휘발성 메모리

CPU가 처리할 데이터가 임시로 저장되는 곳  

Random Access란 데이터를 하나씩 찾기보다 특정위치에 데이터를 직접 저장하거나 검색할 수 있는 방식으로 어느 위치에 저장되어있는 데이터든지 접근하는데 걸리는 시간이 동일하다는 뜻이다.  

하드디스크는 기억이 오래 지속되지만, RAM은 CPU와 직접적으로 교류하며 프로그램 명령을 처리하기 때문에 RAM을 주기억 장치라고 한다.  

>>CPU 와 RAM은 매우 긴밀한 관계이며 어느 하나의 성능이 충분치 못하다면 둘 중 최저성능에 맞춰지게 된다.  
>>CPU가 32bit만 지원한다면 RAM을 8GB를 장착했더라도 4GB밖에 쓰지 못한다.  
>>CPU가 최신이라도 RAM이 512MB라면 CPU의 처리속도보다  
>>작은 용량밖에 RAM에 저장하지 못해 연산속도가 매우 느리다.  





##한글 encoding 종류:sunny:

####UTF-8  

초성,중성,종성을 각각 1바이트로 인식해서 일반적으로 한글을 한 글자에 3바이트로 인식한다. 
조합형이면서 유니코드 인코딩 방식 중 하나다. 유니코드의 경우에는 다른 국가에서 한글 언어팩이 설치되어있지 않은 경우라도 한글 표현이 가능하다.  
다양한 언어로 작성되는 환경이나 웹과 같이 다양한 국가의 사람들이 보는 경우에 좋은 방식이다.  

####EUC-KR  

완성형 인코딩 방식으로 한글을 2바이트로 인식한다. 한글과 영어만 사용하는 페이지에 적합하다.    
CP949은 이 방식의 연장선에 있다. CP949의 경우는 한글 법칙에 의해 만들어 낼 수 있는 모든 문자를 완성형으로 만들어 놓았기 때문에 더이상 표현의 제약은 없다.  
Microsoft에서는 조합형까지 쓸 수 있도록 ms949라는 확장완성형을 내놓았다.    


>>완성형, 조합형에 따른 표현의 제약이 사라졌지만  
>>웹에서는 encoding방식이 꼭 같아야 제대로 문자를 표현할 수 있다.  
>>웹과 서버에서는 기본으로 UTF-8을,  
>>윈도우에서는 완성형 인코딩방식인 EUC-KR이 많이 쓰인다.    
>>둘의 충돌을 해결하기 위해서 다양한 인코딩을 지원하도록 하거나  
>>코딩을 달리하거나 하는 등의 방식이 쓰이고 있다.  


