# 지하철 유동 대시보드

서울교통공사 243개 역의 2024~2025년 시간대별 승하차 인원으로 만든 상권·옥외광고 마케터용 대시보드입니다.

- 라이브 대시보드(Supabase에서 데이터를 읽음): https://menteur-ran.github.io/seoul-subway-dashboard/
- 고정판(데이터 내장): [dashboard.html](https://menteur-ran.github.io/seoul-subway-dashboard/dashboard.html)
- `data.json`: 역별 집계값. Supabase `station_flow` 테이블에 적재하는 원본
- 데이터 출처: 서울교통공사 역별 일별 시간대별 승하차인원(공공데이터포털, 서울 열린데이터광장), 공공누리 1유형
- 서울교통공사 관할 구간만 포함합니다(9호선, 공항철도, 코레일 구간 제외). 승하차 인원은 이동량이지 광고 노출 수가 아닙니다.
