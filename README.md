# 📊 주식 AI 분석기

미국 주식 종목에 대한 AI 기반 실시간 종합 분석 대시보드입니다.

## 🚀 설치 및 실행
Release에서 stocker_streaming.zip파일을 다운받아 압축 해제. stocker_streaming.exe 실행.

## 🔧 실행 화면
실행 시 아래와 같이 동작함을 확인.
```bash
 Serving Flask app 'stocker_streaming'
 Debug mode: on
```
* v1.1부터는 티커 검색기능이 추가됨으로서, 티커 library를 불러들이는 과정이 추가되었습니다.
![image](https://github.com/user-attachments/assets/83c39c5c-e9b5-4fd2-9f8f-09ff4a6fa6ca)

- 접속: http://localhost:8050 또는 서버IP:8050
![image](https://github.com/user-attachments/assets/7a3fe929-2574-4587-b7f0-b05070f72c25)

## 🔧 주요 기능
- 실시간 주가/뉴스/옵션/리스크/오퍼링/AI 종합점수/전략 요약 등 대시보드 제공
- SEC/오퍼링/소송 등 리스크 자동 분석 및 링크 제공
- 대형주 하한선, 긍정 가중치 등 AI 점수 산정 로직 반영
- 감성분석, 번역, 캐싱, 환경변수 등 다양한 부가 기능

## 📝 사용 예시
1. 티커 입력 (예: TSLA, AAPL, NVDA)
2. "분석 시작" 클릭
3. 실시간 AI 종합 분석 결과 확인. 1분마다 갱신됨.

## ⚠️ 투자 유의사항
- 본 서비스는 투자 조언이 아닌 정보 제공 목적입니다.
- 실제 투자 결정 및 책임은 사용자 본인에게 있습니다.
- API 사용량 제한에 주의하세요. 

## 업데이트 내역
### v.1.0
- 기본 기능 Release
### v.1.1
- 티커 검색기능 추가
- 티커 히스토리 기능 추가 
### v.1.2
- 느린 API호출 최적화
- 추가 표기 : 고가/저가(1달내), 총 주식 수, 일일 거래량, 총 거래대금 등 추가
