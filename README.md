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

- 접속: http://localhost:8050 또는 서버IP:8050

## 🔧 주요 기능
- 실시간 주가/뉴스/옵션/리스크/오퍼링/AI 종합점수/전략 요약 등 대시보드 제공
- SEC/오퍼링/소송 등 리스크 자동 분석 및 링크 제공
- 대형주 하한선, 긍정 가중치 등 AI 점수 산정 로직 반영
- 감성분석, 번역, 캐싱, 환경변수 등 다양한 부가 기능

## 📝 사용 예시
1. 티커 입력 (예: TSLA, AAPL, NVDA)
2. "분석 시작" 클릭
3. 실시간 AI 종합 분석 결과 확인. 1분마다 갱신됨.

## 📝 실행화면
![image](https://github.com/user-attachments/assets/872a9c37-c16c-4e97-aeec-c08e68d56948)

## ⚠️ 투자 유의사항
- 본 서비스는 투자 조언이 아닌 정보 제공 목적입니다.
- 실제 투자 결정 및 책임은 사용자 본인에게 있습니다.
- API 사용량 제한에 주의하세요. 
