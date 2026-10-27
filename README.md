# Week 5 — Interactive Generative Poster

Arts and Advanced Big Data / From Colab to the Web

## About
수업 안내 PDF의 Streamlit 예제 코드로 만든 실습용 앱입니다.
원본 blob(), make_palette(), draw_poster()의 그림 생성 규칙을 유지합니다.

## Controls
- Layers: 도형 개수 (3–20)
- Wobble: 도형 윤곽의 불규칙함 (0.01–0.30)
- Palette mode: pastel / vivid / mono / random
- Seed: 난수 번호 (0–9999). 같은 설정과 번호는 같은 결과를 만듭니다.

## Run locally (optional)
```text
python -m pip install -r requirements.txt
python -m streamlit run app.py
```

## Deploy
Streamlit Community Cloud에서 이 저장소의 main 브랜치와 app.py를 선택합니다.

## Source
Prof. Jahwan Koo, Week 5 - From-Colab-to-the-Web-Guide, pp. 4–5.
수업 예제 코드를 실습용으로 옮겼으며 독자적으로 작성한 그림 생성 알고리즘이 아닙니다.
파일 정리와 실행 확인에 OpenAI Codex의 지원을 받았습니다.
