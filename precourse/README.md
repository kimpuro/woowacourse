<h2>프리코스 진행 방식</h2><h3>진행 방식</h3><ul><li>미션은 <strong>과제 진행 요구 사항</strong>, <strong>기능 요구 사항</strong>, <strong>프로그래밍 요구
사항</strong> 세 가지로 구성되어 있다.</li><li>세 개의 요구 사항을 만족하기 위해 노력한다. 특히 기능을 구현하기 전에 기능 목록을 만들고, 기능 단위로 커밋 하는 방식으로
진행한다.</li><li><strong>기능 요구 사항에 기재되지 않은 내용은 스스로 판단하여 구현한다.</strong></li><li>매주 진행할 미션은 화요일 오후 3시부터 확인할 수 있으며, 다음 주 월요일까지
구현을 완료하여 제출해야 한다. <strong>제출은 일요일 오후 3시부터 가능하다.</strong><ul><li><strong>정해진 시간을 지키지 않을 경우 미션을 제출하지 않은 것으로
간주한다.</strong></li><li>종료 일시 이후에는 추가 푸시를 허용하지 않는다.</li></ul></li></ul><h3>미션 제출 방법</h3><ul><li>미션 구현을 완료한 후 GitHub을 통해
제출해야 한다.<ul><li>GitHub을 활용한 제출 방법은 <a href="https://github.com/woowacourse/woowacourse-docs/tree/master/precourse">프리코스
과제 제출</a> 문서를 참고해 제출한다.</li></ul></li><li>GitHub에 미션을 제출한 후 <a href="https://apply.techcourse.co.kr">우아한테크코스 지원 플랫폼</a>에
PR 링크를 포함하여 최종 제출한다.<ul><li>자세한
안내는 <a href="https://github.com/woowacourse/woowacourse-docs/tree/master/precourse#%EC%A0%9C%EC%B6%9C-%EA%B0%80%EC%9D%B4%EB%93%9C">
제출 가이드</a>를 참고한다.</li><li>과제를 수행하면서 느낀 점, 배운 점, 많은 시간을 투자한 부분 등 자유롭게 작성한다.</li></ul></li></ul><h3>과제 제출 전 체크
리스트</h3><ul><li>기능을 올바르게 구현했더라도 <strong>요구 사항에 명시된 출력 형식을 따르지 않으면 0점</strong>을 받게 된다.</li><li>기능 구현을 완료한 후 아래 가이드에 따라 모든
테스트가 성공적으로 실행되는지 확인한다.</li><li><strong>테스트가 실패하면 점수가 0점</strong>이 되므로 제출하기 전에 반드시 확인한다.</li></ul><h4>테스트 실행
가이드</h4><ul><li>터미널에서 <code>node --version</code>을 실행하여 Node.js 버전이 20.17.0 이상인지 확인한다.</li><li>아래 명령을 입력하여 패키지를 설치한 후
실행하는 데 문제가 없어야 한다.</li></ul><pre><code data-highlighted="yes" class="hljs language-routeros">npm install
npm <span class="hljs-built_in">run</span> test
npm <span class="hljs-built_in">run</span> start
</code></pre>