# 채팅 서버 개발로 알아보는 C++의 기술들

C++ 네트워크 프로그래밍 학습시 IOCP사용을 추천한다.<br/>
배웠지만 서버개발이 불가능한 경우
1. 네트워크 지식부족
2. 윈도우 지식부족
3. C++실력 부족
IOCP는 7개의 함수만 알아도됨
1. CreateIoCompletionPort
2. GetQueuedCompletionStatus / PostQueuedCompletionStatus
이번 세션
1. C++17
2. IOCP
3. Windows-only
4. Header-only
함수 실행 시 실패가 어디서 일어났는지 알기 어려움
<br/>C+11의 enum class 사용
하드웨어 등의 변화에 따라 최대 접속가능한 클라이언트 수가 바뀜
<br/>std::vector 사용
멀티스레드
<br/>std::thread(C++11)
메모리 누수
<br/>std::unique_ptr, std::shared_ptr(C++11)
데이터 경합
<br/>std::mutex, std::atomic