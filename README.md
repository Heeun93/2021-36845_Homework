# 2021-36845_Homework

Microbiome analysis with public 16S rRNA sequencing data

개요: 현재 진행하는 연구 프로젝트 중 수업과 밀접하게 관련된 부분이 microbiome analysis이고, 
그 중 16S rRNA sequencing data 분석이 가장 알맞은 것 같아 해당 분석을 진행하기로 함.

목표: Public 16S rRNA sequencing data의 분석 진행 및 시각화(visualization)

진행계획:
1. Qiita (canonically pronounced cheetah) 등의 public DB에서 연구를 선택하여, 16S rRNA sequencing data와 metadata를 취득.
2. Qiime2 기반으로 sequencing quality evaluation, denosing with DADA2, phylogenetic tree analyses, alpha diversity analyses (Shannon, Chao1, Shimpson), 8.	Principal coordinates (PCoA) 등 진행
3. PICRUSt2 기반 taxonomy 분석, visualization (cladogram, LefSe, etc.)
4. Functional analysis based on the cluster of orthologous groups (COG) and Kyoto Encyclopedia of Genes and Genomes (KEGG) annotations
