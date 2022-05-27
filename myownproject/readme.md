Myownproject
============


Purpose
===
**Fig S3C 재현해보기 (transcriptome에서 error가 많이 나오는 부분들 주변 서열을 모아서 문맥을 파악)**

Progress
===
1. 주제 선정 및 논문을 통한 주제 관련 내용 파악
- 선택한 주제 : transcriptome에서 error가 많이 나오는 부분들 주변 서열을 모아서 문맥을 파악 (Fig S3C)
- Cho et al(2012), LIN28A Is a Suppressor of ER-Associated Translation in Embryonic Stem Cells 참고
> Fig 3C : potential LIN28A binding site 주변 패턴 분석
> 분석 결과 : 자주 mutation이 일어나는 G의 위치를 기준으로 앞에는 A, U를 더 선호하는 2개의 base가 오고, A,G를 더 선호하는 3개의 base가 G의 위치 기준으로 뒤에 오는 게 확인됨.

2. 진행 계획
- CLIP35L33G에 대해 pileup & sequence depth에 따른 filtering
- Shannon entropy 계산 및 0.7 기준으로 filtering
 
