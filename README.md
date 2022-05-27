# 2021-36845_Homework

목표: 참고 논문 (LIN28A Is a Suppressor of ER-Associated Translation in Embryonic Stem Cells)의 Fig S2A 재현해보기 
- error가 많이 나오는 부분의 unique sequence들의 각각 개수를 세서 genome browser로 표현하고, 점수 트랙을 같이 표시

진행계획:
1. 기존 Mission에서 다운받았던 gencode.gtf 파일을 이용하여 Mirlet7d locus 위치를 알아냄
2. 1의 좌표 범위로 bam을 솎아냄
3. base별로 Shannon entropy 계산한 후, 이를 높은차순으로 정렬
4. UCSC Genome Browser에 접속해서 visualization
