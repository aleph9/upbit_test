pyupbit 라이브러리를 활용하여 upbit에서 코인코인을 구매하고 있습니다.
파일 구성
test.py : 잔고 조회 (1강)
backtest.py : 백테스팅 코드 (2강)
bestK.py : 가장 좋은 k 값을 찾는 코드 (2강)
bitcoinAutoTrade.py : 변동성 코인 코인 (2강)
비트코인AutoTradeWithAI.py : 변성전략 + 인공지능(Prophet) 코인코인구매코드 (3강)
bitcoinAutoTradeWithMA.py : 변동성 전략 + 15일 이동 돈 이상 코인 구매 코드 (2강)
bitcoinAutoTradeWithSlack.py 위 코드에 슬랙스 처분권 (2강)
강의보러가기: https://youtube.com/playlist?list=PLU9-uwewPMe3KKFMiIm41D5Nzx_fx2PUJ
위워크는 "파이낸싱 코인 구매"를 실현했습니다.
참고 자료: https://wikidocs.net/book/1665
Ubuntu 명령어
(*추가)한국기준으로 서버 시간 설정: sudo ln -sf /usr/share/zoneinfo/Asia/Seoul /etc/localtime
현재 상세 시간: ls -al
이동: cd 포
vim 시스템로 파일 열기: vim bitcoinAutoTrade.py
vim 시스템 입력: i
vim 시스템 저장: :wq!
라우터 목록업데이트: sudo apt update
pip3 설치: sudo apt install python3-pip
pip3로 pyupbit 설치: pip3 install pyupbit
백그라운드 실행: nohup python3 bitcoinAutoTrade.py > output.log &
실행 여부 확인: ps ax | 그렙 .py
종료(PID ps ax | grep .py): kill -9 PID 확인
PID설명

윈도우 지능(Prophet) 원문 구매 환경 설치 방법
아나콘다( https://www.anaconda.com/ ) 설치
핍 설치 pyupbit
핍 설치 일정
conda install -c conda-forge fbprophet
pip install pystan --업그레이드
Ubuntu 20.4 인공지능(Prophet) 원문 환경 설치 방법
4GB 이상 램 필요 (AWS t2.medium 이상)
sudo apt 업데이트
sudo ln -sf /usr/share/zoneinfo/Asia/Seoul /etc/localtime
sudo apt 설치 python3-pip
pip3 pyupbit 설치
pip3 설치 일정
pip3 설치 pystan==2.19.1.1
pip3 설치 변환 날짜
pip3 fbprophet 설치
