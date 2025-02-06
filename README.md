# AI 지식 그래프 생성기 v1.0.1

배포 사이트 링크
https://knowledge-graph-tk.streamlit.app/

## 업데이트 내역
### v1.0.1
- API 키 입력 UI 개선
- Gemini API 키 환경변수 처리
- DeepSeek API 연동 방식 개선
- 모델 선택 UI 개선 (API 키 입력 시 자동 활성화)
- 오류 처리 및 사용자 피드백 개선

### v1.0.0
- 초기 버전 릴리스

## 프로젝트 개요
이 프로젝트는 Streamlit을 활용하여 텍스트를 입력받아 AI 모델들이 자동으로 지식 그래프를 생성하는 웹 애플리케이션입니다.

## 주요 기능
- 여러 AI 모델 지원 (ChatGPT, Gemini, Claude, DeepSeek)
- 텍스트 입력을 통한 지식 그래프 자동 생성
- 실시간 그래프 시각화
- 생성된 그래프 이미지 다운로드


## 설치 방법
1. 저장소 클론
```bash
git clone https://github.com/your-username/knowledge-graph-generator.git
cd knowledge-graph-generator
```

2. 가상환경 생성 및 활성화
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
# 또는
venv\Scripts\activate  # Windows
```

3. 필요한 패키지 설치
```bash
pip install -r requirements.txt
```

4. Graphviz 설치
- Ubuntu/Debian: `sudo apt-get install graphviz`
- macOS: `brew install graphviz`
- Windows: `winget install graphviz`

## 환경 변수 설정
`.env` 파일을 생성하고 다음 API 키들을 설정:
```
OPENAI_API_KEY=your_openai_api_key
GEMINI_API_KEY=your_gemini_api_key
CLAUDE_API_KEY=your_claude_api_key
DEEPSEEK_API_KEY=your_deepseek_api_key
```

## 실행 방법
```bash
streamlit run app.py
```

## 사용 방법
1. 사이드바에서 사용할 AI 모델의 API 키 입력
2. 분석할 텍스트를 입력 창에 입력
3. "지식 그래프 생성" 버튼 클릭
4. 생성된 그래프 확인 및 다운로드

## 기술 스택
- Frontend: Streamlit
- AI Models: OpenAI GPT-4, Google Gemini, Anthropic Claude, DeepSeek
- Visualization: Graphviz
- Language: Python 3.8+

## 라이선스
MIT License

## 기여 방법
1. 이 저장소를 Fork합니다
2. 새로운 Branch를 생성합니다 (`git checkout -b feature/AmazingFeature`)
3. 변경사항을 Commit합니다 (`git commit -m 'Add some AmazingFeature'`)
4. Branch에 Push합니다 (`git push origin feature/AmazingFeature`)
5. Pull Request를 생성합니다

## 문의사항
이슈를 통해 문의해주세요. 
