#RAM이란 무엇인가?#

RAM을 알기전에 ROM이라는게 있다.RAM ROM 뭔가 비스무레한게 연관이 되어있을거라고 생각했다.
어디서 주워들어서 ROM이라는게 Read Only Memory 라는건 알겠는데, 해석해보면 오직 읽는 메모리??라는데 쓰지는 못하고 읽기만 가능한 메모리인가보다.
그래서 RAM 도  Read ??? Memory인가 예상을 했는데, 반만 맞더라.

RAM(Random Access Memory) 무작위 접근 메모리? 라는데 솔직히 뭔말인지 잘 모르겠다.
두산백과에 따르면 <http://terms.naver.com/entry.nhn?docId=1087343&cid=40942&categoryId=32832> 라며
RAM은 기억된 정보를 읽어내기도 하고 다른 정보를기억시킬 수 있는 메모리 라고 한다.

ROM
:   전원이 들어오면 무슨 작업을 해야할지 미리 프로그램이 되어있는 장치,전원을 넣으면 주변장치가 있는지 확인하고 사용가능한 상태로 만든다. 이후 윈도우가 실행되기 위해 필요한 각종 장치등을 메모리에 로드하게 되는게 

RAM
:   전원이 켜지면 다시 기억해 내는것이 아니고 컴퓨터를 사용하면서 램을 사용하는것. 저장을 하지않는 '휘발성' 데이터를 일시적으로 저장할 뿐 컴퓨터를 끄면 데이터가 날아간다.

---

#한글을 표현 할 수 있는 인코딩 방식#
한글 인코딩 방식은 크게 두가지로 나뉜단다. UTF-8(이건 나도 많이 들어봄) 과 EUC-KR(듣보..) 

UTF-8 뭔가 자주 들어본거같고 뭔가 자주 쓰이는거같고 뭔가 자주쓴다니 좋아보이긴 하는데 솔직히 뭔지 잘 모른다.
UTF-8
: 유니코드.EUC-KR과는 다르게 UTF-8은 전세계 모든 문자를 동일하게 표현할 수 있는 인코딩 방식. 이 방식은 구글,페이스북,트위터 등 굵직굵직한 사이트에서도 사용한다니 짱짱이긴 한데 한글은 3byte로 처리하기 떄문에 문서가 다소 커질 수 있다고 한다.

EUC-KR
: Extend unix code의 약자로 영어를 제외한 문자를 표현하귀 위한 확장부호란다. KR 인거보니까 한글관련인거같은데 진짜 한글 표현을 위한 문자 인코딩 방식이란다.한글 한 자를 2byte로 처리해서 UTF-8보다는 문서가 작을것이다.

UTF-8 과 EUC-KR
:  한글 한 자를 3byte에 처리하는 UTF-8에 비해선 EUC-KR이 2byte로 처리 가능하기때문에, 한글 위주의 사이트에선 유리하겠다. 한국에서만 작게 한국에서만 할거면 EUC-KR로 하는게 좋을거같은데, 성장해서 다른 지역까지 바라보게 된다면 UTF-8을 쓰는게 더 좋을거 같다. 어차피 바뀌게 될지도 모르는거 개인적으로는 처음부터 UTF-8을 하는게 좋지않을지...?

도움 : <http://blog.naver.com/hostinggodo/220587160173> 
