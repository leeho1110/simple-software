# simple-software
맥스 카넷-알렉산더의 서적 '심플 소프트웨어'을 읽고 정리한 레포지토리입니다.

---

### 서평

F-lab 멘토링 오리엔테이션 내 멘티분을 소개하는 시간에 경품으로 당첨된 서적입니다. 당시 기술도 중요하지만 어떤 개발자가 되고 싶은지에 대한 고민이 많았습니다. 그러려면 스스로에게 어떤 개발자가 되어야 하는지 고민해보고 실루엣을 그리는 과정이 필요했어요. 기술은 변해도 의식은 변하지 말자고 다짐했었거든요. 코드를 떠나 소프트웨어를 다루는 사람으로써 어떤 마음가짐을 가져야 하는지에 대해 많은 도움을 받았습니다.

---

### Q&A

- ***Q. ‘좋은’ 개발자라는 것은 본인이 정의하기에 따라 많이 달라집니다. 만약 그런 사람이 되고 싶다면 가장 먼저 해야할 일은 무엇일까요?***
    
    좋은 개발자가 되고 싶다는 마음입니다. 사실 좋은 개발자를 만들기 위한 이론은 충분합니다. 하지만 그것이 입에서만 나온다면 흔히 말하는 ‘입개발자’가 되겠죠. 입 끝에선 향기가 나는 것 같아도, 손 끝에선 악취만 풍긴다면 좋은 개발자가 아닐 가능성이 높다고 생각해요. 입개발자가 되지 않도록 행동으로 보여주는 자세를 가지려 노력중입니다.
    
- ***Q. 코드에 주인의식을 가지는 것, 꼭 필요할까요?***
    
    네. 반드시 필요합니다. 주인 의식과 책임감을 갖고 더러운 코드를 남기지 않겠다는 사명이 필요하다고 느껴요. 최근엔 스스로에게 이런 질문을 많이 하는 것 같습니다. 
    
    > “*만약 지금 작성하는 코드가 내 방이 된다면 이대로 커밋할거야?”*
    > 
    
    기능이 추가되는 경우에도 마찬가지입니다. 요청이 들어왔다고 곧바로 시작하는 것이 아니라 이야기를 나누며 어떤 목적으로 추가하게 됐는지 같이 이야기하는 시간이 필요하다고 느낍니다. 분명 요청을 해주신 분이 심사숙고해서 결정해주셨겠지만요.
    
    기능의 추가는 관리 포인트의 증가이며 해당 기능을 사용하는지 않는지는 개발자가 알아차리기 쉽지 않습니다. 기획자분들이 “이 기능은 사용하지 않으니 빼주세요" 라고 말하는 경우는 거의 없었거든요. 다니고 있는 회사 백오피스엔 이렇게 남아있는게 무려 170개나 되거든요.
    
    개발자는 항상 팀으로 일하니까요. 동료들이 알아보지 못하는 코드를 작성해놓고 나몰라라 하는 행동은 좋은 동료로 보기엔 많이 부족한 모습이지 않을까요.
    
- ***Q. 중복, 진짜 싫어해야 할까요?***
    
    싫어하는 것만으로는 부족하고, 심지어 끔찍하게 싫어해야 합니다. 남겨놓은 중복은 부메랑이 되어 돌아옵니다. 중복이 유발하는 문제는 단순히 수정을 ‘N 번'해야된다는 사실로부터 시작해서 수많은 문제를 유발해요. 주기적이고 습관적인 리팩토링이 쉽지 않지만 노력해야겠죠.
    
    미래를 예측하지 않는 자세도 중요한 것 같아요. 어차피 미래는 틀려도 문제, 맞아도 문제에요. 틀리면 다시 만들어야하니 문제이고 맞았다면 다음에도 맞출 수 있을거란 어리석은 자신감을 심어주기 때문에 문제입니다.
    
    태풍은 반드시 온다. 미래를 예측해 절대 다치지 않겠다고 생각하지 말고 소프트웨어가 갖춰야할 견고한 설계를 통해 안아프게 맞는 것이 더 옳다고 느껴요.
    
- ***Q. 리팩토링, 어떻게 하고 계신가요?***
    
    > *리팩토링을 위한 리팩토링을 한다면 리팩토링의 이름에 먹칠을 하는 것이나 다름없다.*
    > 
    
    정확히 저였습니다. 리팩토링이 목적인 리팩토링을 하고 있었거든요. 물론 요구사항과 아예 관련없는 코드는 아니었지만 제품과 시스템의 기능적 목표와 관련이 없는 리팩토링이 적지 않은 비율을 차지했었습니다. 
    
    본문에서 이런 리팩토링은 아무도 관심을 보이지 않는 쓸모 없는 물건을 정리하는 행위처럼 아무것도 성취하지 못한다고 말하는데요. 완벽하게 동의하게 됐습니다. 
    
    결국 소프트웨어 개발자는 사용자에게 제공해야하는 서비스를 소프트웨어를 통해 제공하는 것이 목표라고 생각해요. 다만 방법이 코드일 뿐이죠. 코드가 줄 수 있는 비즈니스 가치가 얼마나 되는지를 망각하면 안됩니다. 본질을 잊고 수단에 홀려 이상한 곳으로 빠지지 말자고 항상 다짐하려 합니다.
    
- **Q. 소프트 스킬, 중요할까요?**
    
    많이 중요하다고 느낍니다. 여러 개선 시도들을 실패했었는데 회고해보니 결과적으로는 소프트 스킬의 부족이었던 것 같아서요. 
    
    심리적 안정감을 가졌는지, 개선 포인트에 대해서 그 사람의 입장에서 도움이 될만했는지 부족한 점이 많았던 것 같아요. 존 손메즈의 서적 ‘소프트 스킬’을 죄책감 바구니(장바구니)에 넣어놓았는데 얼른 읽으러 가야겠네요.
