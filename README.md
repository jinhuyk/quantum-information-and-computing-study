# Quantum Information and Computing (KOR)

IBM Quantum Information & Computation 코스를 따라가며 정리한 한국어 노트입니다. 필요한 경우 Nielsen & Chuang의 "양자계산과 양자정보" 내용을 보완 자료로 인용합니다.

## 구성
- `docs/docs.tex`: LaTeX 원문
- `docs/docs.pdf`: 컴파일된 PDF
- `tutorial/course1.ipynb`: 코스 1 실습 노트북

## PDF 빌드
KoTeX가 포함된 LaTeX 환경이 필요합니다.

```bash
latexmk -xelatex -file-line-error -interaction=nonstopmode -output-directory=docs docs/docs.tex
```

`latexmk`가 없다면 다음과 같이 빌드할 수 있습니다.

```bash
xelatex -file-line-error -interaction=nonstopmode -output-directory=docs docs/docs.tex
xelatex -file-line-error -interaction=nonstopmode -output-directory=docs docs/docs.tex
```

## 노트북 실행
Jupyter 환경에서 `tutorial/course1.ipynb`를 열어 실행하세요.
