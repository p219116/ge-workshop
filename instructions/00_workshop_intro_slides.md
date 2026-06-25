# 💻 Gemini Enterprise 실습 워크숍 발표 장표 (Slide Deck)

본 문서는 **홍익대학교 교수와 임직원을 위한 Gemini Enterprise 핸즈온 워크숍** 진행 시 각 실습 세션을 시작하기 전, 참가자들에게 각 단계의 목적, 시나리오 및 핵심 기능을 한눈에 직관적으로 소개할 수 있도록 디자인된 **프레젠테이션 장표 가이드**입니다.

각 슬라이드는 현대적이고 세련된 카드 레이아웃과 컬러 그라데이션 테마로 설계되어, 브라우저나 GitHub 화면에서 직접 프레젠테이션용 장표로 활용하기에 최적화되어 있습니다.

---

<!-- SLIDE 1: Title Slide -->
<div style="
  background: linear-gradient(135deg, #0f172a 0%, #1e3a8a 50%, #1e40af 100%);
  color: #ffffff;
  padding: 50px 40px;
  border-radius: 24px;
  box-shadow: 0 20px 40px rgba(0, 0, 0, 0.3);
  font-family: 'Outfit', 'Inter', 'Noto Sans KR', sans-serif;
  margin-bottom: 50px;
  border: 1px solid rgba(255, 255, 255, 0.1);
">
  <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 30px;">
    <span style="background: rgba(255, 255, 255, 0.15); color: #60a5fa; padding: 6px 16px; border-radius: 50px; font-size: 14px; font-weight: 600; letter-spacing: 1px;">WELCOME SLIDE</span>
    <span style="color: rgba(255, 255, 255, 0.5); font-size: 14px;">Hongik University × Gemini Enterprise</span>
  </div>
  <h1 style="font-size: 34px; line-height: 1.35; font-weight: 800; margin: 0 0 20px 0; background: linear-gradient(90deg, #ffffff 0%, #93c5fd 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent;">
    🎨 홍익대학교 교수·임직원을 위한<br>Gemini Enterprise 실습 워크숍
  </h1>
  <p style="font-size: 16px; color: #cbd5e1; line-height: 1.6; margin: 0 0 35px 0; max-width: 680px;">
    단순한 AI 채팅을 넘어 대학 행정업무 자동화, 고도화된 융합 학술 연구, 그리고 혁신적인 교수법(Pedagogy) 설계를 완수하는 AI 협업 워크플로우를 체득합니다.
  </p>
  <div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 20px; border-top: 1px solid rgba(255, 255, 255, 0.1); padding-top: 30px;">
    <div>
      <div style="font-size: 12px; color: #94a3b8; margin-bottom: 5px; text-transform: uppercase;">Target</div>
      <div style="font-size: 15px; font-weight: 600; color: #f8fafc;">홍익대 교수진 & 행정 임직원</div>
    </div>
    <div>
      <div style="font-size: 12px; color: #94a3b8; margin-bottom: 5px; text-transform: uppercase;">Total Modules</div>
      <div style="font-size: 15px; font-weight: 600; color: #f8fafc;">6개 실무 맞춤 세션</div>
    </div>
    <div>
      <div style="font-size: 12px; color: #94a3b8; margin-bottom: 5px; text-transform: uppercase;">Key Value</div>
      <div style="font-size: 15px; font-weight: 600; color: #38bdf8;">보안이 강화된 업무 생산성 극대화</div>
    </div>
  </div>
</div>

---

<!-- SLIDE 2: Workshop Roadmap -->
<div style="
  background: #ffffff;
  color: #1e293b;
  padding: 45px 40px;
  border-radius: 24px;
  box-shadow: 0 15px 35px rgba(0, 0, 0, 0.05);
  font-family: 'Inter', 'Noto Sans KR', sans-serif;
  margin-bottom: 50px;
  border: 1px solid #e2e8f0;
">
  <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 25px;">
    <span style="background: #eff6ff; color: #1d4ed8; padding: 6px 16px; border-radius: 50px; font-size: 13px; font-weight: 700;">AGENDA & MAP</span>
    <span style="color: #64748b; font-size: 14px; font-weight: 500;">전체 실습 로드맵</span>
  </div>
  <h2 style="font-size: 26px; font-weight: 800; color: #0f172a; margin: 0 0 15px 0;">🗺️ 워크숍 실습 연계 워크플로우</h2>
  <p style="font-size: 14px; color: #64748b; margin: 0 0 30px 0; line-height: 1.5;">
    딥리서치가 백그라운드에서 구동되는 시간 동안 데이터를 분석하고, 완료된 학술 리포트를 NotebookLM과 연결하여 교수법을 기획하는 유기적인 연계 과정입니다.
  </p>
  
  <div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 15px;">
    <!-- Step 1-2 -->
    <div style="background: #f8fafc; padding: 20px; border-radius: 16px; border-left: 5px solid #f97316;">
      <div style="font-size: 13px; font-weight: 800; color: #ea580c; margin-bottom: 8px;">PHASE 1. 연구 개시 & 분석</div>
      <div style="font-size: 14px; font-weight: 700; color: #334155; margin-bottom: 5px;">01. Deep Research (다)</div>
      <div style="font-size: 12px; color: #64748b; line-height: 1.4; margin-bottom: 10px;">글로벌 융합 연구 동향 탐색 (백그라운드 실행)</div>
      <div style="font-size: 14px; font-weight: 700; color: #334155; margin-bottom: 5px;">02. Excel 분석 및 시각화 (가)</div>
      <div style="font-size: 12px; color: #64748b; line-height: 1.4;">학생 만족도 다차원 요약 및 PPT 기획</div>
    </div>
    <!-- Step 3-4 -->
    <div style="background: #f8fafc; padding: 20px; border-radius: 16px; border-left: 5px solid #0ca678;">
      <div style="font-size: 13px; font-weight: 800; color: #0ca678; margin-bottom: 8px;">PHASE 2. 행정 탐색 & 설계</div>
      <div style="font-size: 14px; font-weight: 700; color: #334155; margin-bottom: 5px;">03. Search Company Data (나)</div>
      <div style="font-size: 12px; color: #64748b; line-height: 1.4; margin-bottom: 10px;">보안 드라이브 내 교내 행정 문서 RAG 검색</div>
      <div style="font-size: 14px; font-weight: 700; color: #334155; margin-bottom: 5px;">04. NotebookLM 교수법 설계 (라)</div>
      <div style="font-size: 12px; color: #64748b; line-height: 1.4;">학술 리포트 + 본교 학사제도 기반 강의 설계</div>
    </div>
    <!-- Step 5-6 -->
    <div style="background: #f8fafc; padding: 20px; border-radius: 16px; border-left: 5px solid #7048e8;">
      <div style="font-size: 13px; font-weight: 800; color: #7048e8; margin-bottom: 8px;">PHASE 3. 지능형 편의 도구</div>
      <div style="font-size: 14px; font-weight: 700; color: #334155; margin-bottom: 5px;">05. MCP 서버 연동 에이전트 (마)</div>
      <div style="font-size: 12px; color: #64748b; line-height: 1.4; margin-bottom: 10px;">구내식당 알리미 맞춤형 에이전트(Low-Code) 빌드</div>
      <div style="font-size: 14px; font-weight: 700; color: #334155; margin-bottom: 5px;">06. Chrome Integration (바)</div>
      <div style="font-size: 12px; color: #64748b; line-height: 1.4;">주소창 단축키(ge) 기반 초고속 검색 환경 구성</div>
    </div>
  </div>
</div>

---

<!-- SLIDE 3: Module 1 (Deep Research) -->
<div style="
  background: linear-gradient(135deg, #fff9db 0%, #fff4e6 100%);
  color: #2b2b2b;
  padding: 45px 40px;
  border-radius: 24px;
  box-shadow: 0 15px 35px rgba(240, 140, 0, 0.1);
  font-family: 'Inter', 'Noto Sans KR', sans-serif;
  margin-bottom: 50px;
  border: 1px solid #ffe8cc;
">
  <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 20px;">
    <span style="background: #ffe8cc; color: #d9480f; padding: 6px 16px; border-radius: 50px; font-size: 13px; font-weight: 800; letter-spacing: 0.5px;">실습 다 (01)</span>
    <span style="color: #d9480f; font-weight: 700; font-size: 14px;">⏱️ 백그라운드 구동형 실습 (소요시간: 5~10분)</span>
  </div>
  <h2 style="font-size: 28px; font-weight: 800; color: #d9480f; margin: 0 0 8px 0;">🔬 심층 학술 동향 조사 (Deep Research)</h2>
  <div style="font-size: 16px; font-weight: 500; color: #862e01; margin-bottom: 25px;">글로벌 대학의 AI 융합 연구 모델 및 우수 산학협력 체계 탐색</div>

  <div style="display: grid; grid-template-columns: 1.2fr 1fr; gap: 30px;">
    <!-- Left Column: Purpose & Scenario -->
    <div>
      <div style="margin-bottom: 20px;">
        <div style="font-size: 13px; font-weight: 800; color: #d9480f; margin-bottom: 5px; text-transform: uppercase;">🎯 실습 목적</div>
        <ul style="font-size: 14px; color: #495057; line-height: 1.6; margin: 0; padding-left: 20px;">
          <li>수십 개의 심층 웹 문서를 AI가 연쇄 검색하고 교차 분석하는 기법 이해</li>
          <li>단발성 검색의 한계를 넘는 전문적 수준의 융합 학술 기획서 자동 집필</li>
        </ul>
      </div>
      <div>
        <div style="font-size: 13px; font-weight: 800; color: #d9480f; margin-bottom: 5px; text-transform: uppercase;">🎬 비즈니스 시나리오</div>
        <p style="font-size: 14px; color: #495057; line-height: 1.6; margin: 0;">
          학제 융합을 추진하는 교직원으로서, 글로벌 탑티어 공대의 산학협력 융합 트렌드를 수집하여 <strong>'글로벌 공학 융합 연구 동향 보고서'</strong> 초안 작성을 지시합니다.
        </p>
      </div>
    </div>
    <!-- Right Column: Tech & Outputs -->
    <div style="background: rgba(255, 255, 255, 0.6); padding: 20px; border-radius: 16px; border: 1px solid rgba(240, 140, 0, 0.15);">
      <div style="margin-bottom: 15px;">
        <div style="font-size: 12px; font-weight: 800; color: #d9480f; margin-bottom: 4px;">🛠️ 핵심 사용 기능</div>
        <div style="display: flex; flex-wrap: wrap; gap: 6px;">
          <span style="background: #fff; border: 1px solid #ffe8cc; color: #d9480f; font-size: 12px; padding: 4px 10px; border-radius: 6px; font-weight: 600;">Deep Research 엔진</span>
          <span style="background: #fff; border: 1px solid #ffe8cc; color: #d9480f; font-size: 12px; padding: 4px 10px; border-radius: 6px; font-weight: 600;">구글 Docs 내보내기</span>
        </div>
      </div>
      <div>
        <div style="font-size: 12px; font-weight: 800; color: #d9480f; margin-bottom: 6px;">🎁 최종 기대 산출물</div>
        <div style="font-size: 14px; font-weight: 700; color: #212529; display: flex; align-items: center; gap: 8px;">
          📄 구글 드라이브 문서 (Google Docs)
        </div>
        <div style="font-size: 12px; color: #6b7280; line-height: 1.4; margin-top: 4px;">
          "글로벌 공학 융합 연구 동향 보고서.gdoc" (이후 실습 라. NotebookLM에서 직접 연계 활용됩니다.)
        </div>
      </div>
    </div>
  </div>
</div>

---

<!-- SLIDE 4: Module 2 (Excel Analysis) -->
<div style="
  background: linear-gradient(135deg, #e6fcf5 0%, #c3fae8 100%);
  color: #12b886;
  padding: 45px 40px;
  border-radius: 24px;
  box-shadow: 0 15px 35px rgba(12, 166, 120, 0.1);
  font-family: 'Inter', 'Noto Sans KR', sans-serif;
  margin-bottom: 50px;
  border: 1px solid #96f2d7;
">
  <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 20px;">
    <span style="background: #96f2d7; color: #087f5b; padding: 6px 16px; border-radius: 50px; font-size: 13px; font-weight: 800; letter-spacing: 0.5px;">실습 가 (02)</span>
    <span style="color: #087f5b; font-weight: 700; font-size: 14px;">📊 데이터 중심 의사결정 실습</span>
  </div>
  <h2 style="font-size: 28px; font-weight: 800; color: #087f5b; margin: 0 0 8px 0;">📊 Excel 데이터 분석 및 PPT 기획</h2>
  <div style="font-size: 16px; font-weight: 500; color: #099268; margin-bottom: 25px;">행정 서베이 정량 데이터 입체 분석 및 AI 기반 프레젠테이션 설계</div>

  <div style="display: grid; grid-template-columns: 1.2fr 1fr; gap: 30px;">
    <!-- Left Column: Purpose & Scenario -->
    <div>
      <div style="margin-bottom: 20px;">
        <div style="font-size: 13px; font-weight: 800; color: #087f5b; margin-bottom: 5px; text-transform: uppercase;">🎯 실습 목적</div>
        <ul style="font-size: 14px; color: #212529; line-height: 1.6; margin: 0; padding-left: 20px;">
          <li>파이썬 코드 실행 없이 정성/정량 만족도 서베이 자료를 즉시 가공하는 기법 습득</li>
          <li>수치 데이터 이면의 잠재적 불만 사항을 파악하는 감성 분석(Sentiment) 수행</li>
        </ul>
      </div>
      <div>
        <div style="font-size: 13px; font-weight: 800; color: #087f5b; margin-bottom: 5px; text-transform: uppercase;">🎬 비즈니스 시나리오</div>
        <p style="font-size: 14px; color: #212529; line-height: 1.6; margin: 0;">
          학사지원팀 담당자로서 신입생 및 재학생들의 <strong>학사행정_학생서베이_샘플.xlsx</strong> 데이터를 바탕으로, 핵심 원인 분석 및 개선 방향을 도출하여 PPT 보고 장표 아웃라인을 설계합니다.
        </p>
      </div>
    </div>
    <!-- Right Column: Tech & Outputs -->
    <div style="background: rgba(255, 255, 255, 0.6); padding: 20px; border-radius: 16px; border: 1px solid rgba(12, 166, 120, 0.15);">
      <div style="margin-bottom: 15px;">
        <div style="font-size: 12px; font-weight: 800; color: #087f5b; margin-bottom: 4px;">🛠️ 핵심 사용 기능</div>
        <div style="display: flex; flex-wrap: wrap; gap: 6px;">
          <span style="background: #fff; border: 1px solid #96f2d7; color: #087f5b; font-size: 12px; padding: 4px 10px; border-radius: 6px; font-weight: 600;">데이터 업로드</span>
          <span style="background: #fff; border: 1px solid #96f2d7; color: #087f5b; font-size: 12px; padding: 4px 10px; border-radius: 6px; font-weight: 600;">텍스트 감성 분류</span>
          <span style="background: #fff; border: 1px solid #96f2d7; color: #087f5b; font-size: 12px; padding: 4px 10px; border-radius: 6px; font-weight: 600;">시각화 차트 추천</span>
        </div>
      </div>
      <div>
        <div style="font-size: 12px; font-weight: 800; color: #087f5b; margin-bottom: 6px;">🎁 최종 기대 산출물</div>
        <div style="font-size: 14px; font-weight: 700; color: #212529; display: flex; align-items: center; gap: 8px;">
          📊 분석 통계표 & 보고 장표 아웃라인 (Markdown)
        </div>
        <div style="font-size: 12px; color: #6b7280; line-height: 1.4; margin-top: 4px;">
          분포 요약, 학부별 차이점 도출 및 10장 규모의 PPT 발표 시나리오 초안 구조 확보
        </div>
      </div>
    </div>
  </div>
</div>

---

<!-- SLIDE 5: Module 3 (Search Company Data) -->
<div style="
  background: linear-gradient(135deg, #e6fcf5 0%, #c3fae8 100%);
  color: #12b886;
  padding: 45px 40px;
  border-radius: 24px;
  box-shadow: 0 15px 35px rgba(12, 166, 120, 0.1);
  font-family: 'Inter', 'Noto Sans KR', sans-serif;
  margin-bottom: 50px;
  border: 1px solid #96f2d7;
">
  <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 20px;">
    <span style="background: #96f2d7; color: #087f5b; padding: 6px 16px; border-radius: 50px; font-size: 13px; font-weight: 800; letter-spacing: 0.5px;">실습 나 (03)</span>
    <span style="color: #087f5b; font-weight: 700; font-size: 14px;">📂 외부 유출 없는 내부 지식 기반 RAG</span>
  </div>
  <h2 style="font-size: 28px; font-weight: 800; color: #087f5b; margin: 0 0 8px 0;">📂 Drive 문서 기반 보안 행정 안내 (RAG)</h2>
  <div style="font-size: 16px; font-weight: 500; color: #099268; margin-bottom: 25px;">학교 구글 공유 드라이브 실시간 연동을 통한 문서 검색 및 정확한 출처 확보</div>

  <div style="display: grid; grid-template-columns: 1.2fr 1fr; gap: 30px;">
    <!-- Left Column: Purpose & Scenario -->
    <div>
      <div style="margin-bottom: 20px;">
        <div style="font-size: 13px; font-weight: 800; color: #087f5b; margin-bottom: 5px; text-transform: uppercase;">🎯 실습 목적</div>
        <ul style="font-size: 14px; color: #212529; line-height: 1.6; margin: 0; padding-left: 20px;">
          <li>보안이 유지된 교내 공유 드라이브의 실제 내부 최신 문서에서 정보를 정확히 검색</li>
          <li>임의 정보 생성을 철저히 방지하고 출처(Source Docs) 링크를 실시간 연쇄 검증</li>
        </ul>
      </div>
      <div>
        <div style="font-size: 13px; font-weight: 800; color: #087f5b; margin-bottom: 5px; text-transform: uppercase;">🎬 비즈니스 시나리오</div>
        <p style="font-size: 14px; color: #212529; line-height: 1.6; margin: 0;">
          행정 부서에서 교직원 대면 교육 기획 중, "Gemini 기초연수 강의 기획서" 내부 파일을 일일이 열어보지 않고 연수 강사 프로필과 할당되는 테스트 에이전트 수를 순식간에 요약 보고해야 합니다.
        </p>
      </div>
    </div>
    <!-- Right Column: Tech & Outputs -->
    <div style="background: rgba(255, 255, 255, 0.6); padding: 20px; border-radius: 16px; border: 1px solid rgba(12, 166, 120, 0.15);">
      <div style="margin-bottom: 15px;">
        <div style="font-size: 12px; font-weight: 800; color: #087f5b; margin-bottom: 4px;">🛠️ 핵심 사용 기능</div>
        <div style="display: flex; flex-wrap: wrap; gap: 6px;">
          <span style="background: #fff; border: 1px solid #96f2d7; color: #087f5b; font-size: 12px; padding: 4px 10px; border-radius: 6px; font-weight: 600;">Google Drive 연동</span>
          <span style="background: #fff; border: 1px solid #96f2d7; color: #087f5b; font-size: 12px; padding: 4px 10px; border-radius: 6px; font-weight: 600;">@참조 기법</span>
          <span style="background: #fff; border: 1px solid #96f2d7; color: #087f5b; font-size: 12px; padding: 4px 10px; border-radius: 6px; font-weight: 600;">Sources 링크 탐색</span>
        </div>
      </div>
      <div>
        <div style="font-size: 12px; font-weight: 800; color: #087f5b; margin-bottom: 6px;">🎁 최종 기대 산출물</div>
        <div style="font-size: 14px; font-weight: 700; color: #212529; display: flex; align-items: center; gap: 8px;">
          🔍 신뢰도 100%의 출처 기반 행정 분석 리포트
        </div>
        <div style="font-size: 12px; color: #6b7280; line-height: 1.4; margin-top: 4px;">
          드라이브 내 '기초연수_기획안' 원본 파일 출처가 명시된 사실적 답변 수집
        </div>
      </div>
    </div>
  </div>
</div>

---

<!-- SLIDE 6: Module 4 (NotebookLM) -->
<div style="
  background: linear-gradient(135deg, #fff9db 0%, #fff4e6 100%);
  color: #2b2b2b;
  padding: 45px 40px;
  border-radius: 24px;
  box-shadow: 0 15px 35px rgba(240, 140, 0, 0.1);
  font-family: 'Inter', 'Noto Sans KR', sans-serif;
  margin-bottom: 50px;
  border: 1px solid #ffe8cc;
">
  <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 20px;">
    <span style="background: #ffe8cc; color: #d9480f; padding: 6px 16px; border-radius: 50px; font-size: 13px; font-weight: 800; letter-spacing: 0.5px;">실습 라 (04)</span>
    <span style="color: #d9480f; font-weight: 700; font-size: 14px;">🎓 교육공학 & 교수법 혁신 실습</span>
  </div>
  <h2 style="font-size: 28px; font-weight: 800; color: #d9480f; margin: 0 0 8px 0;">📝 NotebookLM 기반 교과목 설계</h2>
  <div style="font-size: 16px; font-weight: 500; color: #862e01; margin-bottom: 25px;">동향 연구 보고서 + 본교 학사 규정 + 멀티미디어(유튜브) 정보의 입체적 설계</div>

  <div style="display: grid; grid-template-columns: 1.2fr 1fr; gap: 30px;">
    <!-- Left Column: Purpose & Scenario -->
    <div>
      <div style="margin-bottom: 20px;">
        <div style="font-size: 13px; font-weight: 800; color: #d9480f; margin-bottom: 5px; text-transform: uppercase;">🎯 실습 목적</div>
        <ul style="font-size: 14px; color: #495057; line-height: 1.6; margin: 0; padding-left: 20px;">
          <li>제공한 특정 파일 그룹에만 100% 철저히 기반하여 동작하는 맞춤 연구 조교 구축</li>
          <li>텍스트, PDF 문서, 유튜브 동영상을 다각도로 활용하는 멀티모달 설계 능력 습득</li>
        </ul>
      </div>
      <div>
        <div style="font-size: 13px; font-weight: 800; color: #d9480f; margin-bottom: 5px; text-transform: uppercase;">🎬 비즈니스 시나리오</div>
        <p style="font-size: 14px; color: #495057; line-height: 1.6; margin: 0;">
          자율전공학부 전임교수로서, (실습 다)에서 도출한 글로벌 연구 동향 보고서와 홍익대학교 자율전공 학사제도 PDF를 융합하여 <strong>'AI 융합공학 맛보기 캡스톤 디자인' 4주 강의 계획서</strong>를 출판 수준으로 설계합니다.
        </p>
      </div>
    </div>
    <!-- Right Column: Tech & Outputs -->
    <div style="background: rgba(255, 255, 255, 0.6); padding: 20px; border-radius: 16px; border: 1px solid rgba(240, 140, 0, 0.15);">
      <div style="margin-bottom: 15px;">
        <div style="font-size: 12px; font-weight: 800; color: #d9480f; margin-bottom: 4px;">🛠️ 핵심 사용 기능</div>
        <div style="display: flex; flex-wrap: wrap; gap: 6px;">
          <span style="background: #fff; border: 1px solid #ffe8cc; color: #d9480f; font-size: 12px; padding: 4px 10px; border-radius: 6px; font-weight: 600;">Discover Sources</span>
          <span style="background: #fff; border: 1px solid #ffe8cc; color: #d9480f; font-size: 12px; padding: 4px 10px; border-radius: 6px; font-weight: 600;">유튜브·PDF 원천 연동</span>
          <span style="background: #fff; border: 1px solid #ffe8cc; color: #d9480f; font-size: 12px; padding: 4px 10px; border-radius: 6px; font-weight: 600;">오디오 팟캐스트 요약</span>
        </div>
      </div>
      <div>
        <div style="font-size: 12px; font-weight: 800; color: #d9480f; margin-bottom: 6px;">🎁 최종 기대 산출물</div>
        <div style="font-size: 14px; font-weight: 700; color: #212529; display: flex; align-items: center; gap: 8px;">
          📖 AI 기반 교육 설계 보고서 & 🎙️ 영문 팟캐스트 오디오
        </div>
        <div style="font-size: 12px; color: #6b7280; line-height: 1.4; margin-top: 4px;">
          학제 진입 장벽을 낮추는 교육 방법론(Pedagogy) 및 슬라이드 발표 장표 원본 자료 획득
        </div>
      </div>
    </div>
  </div>
</div>

---

<!-- SLIDE 7: Module 5 (MCP Server) -->
<div style="
  background: linear-gradient(135deg, #f3f0ff 0%, #e8dbfc 100%);
  color: #7048e8;
  padding: 45px 40px;
  border-radius: 24px;
  box-shadow: 0 15px 35px rgba(112, 72, 232, 0.1);
  font-family: 'Inter', 'Noto Sans KR', sans-serif;
  margin-bottom: 50px;
  border: 1px solid #d0bfff;
">
  <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 20px;">
    <span style="background: #d0bfff; color: #5f3dc4; padding: 6px 16px; border-radius: 50px; font-size: 13px; font-weight: 800; letter-spacing: 0.5px;">실습 마 (05)</span>
    <span style="color: #5f3dc4; font-weight: 700; font-size: 14px;">🔌 나만의 맞춤 지능형 에이전트 빌딩</span>
  </div>
  <h2 style="font-size: 28px; font-weight: 800; color: #5f3dc4; margin: 0 0 8px 0;">🔌 MCP 기반 구내식당 알리미 개발</h2>
  <div style="font-size: 16px; font-weight: 500; color: #6741d9; margin-bottom: 25px;">외부 데이터베이스(API)와 실시간 구글 검색을 도구로 활용하는 로우코드 에이전트 구축</div>

  <div style="display: grid; grid-template-columns: 1.2fr 1fr; gap: 30px;">
    <!-- Left Column: Purpose & Scenario -->
    <div>
      <div style="margin-bottom: 20px;">
        <div style="font-size: 13px; font-weight: 800; color: #5f3dc4; margin-bottom: 5px; text-transform: uppercase;">🎯 실습 목적</div>
        <ul style="font-size: 14px; color: #495057; line-height: 1.6; margin: 0; padding-left: 20px;">
          <li>실시간 구내식당 식단 정보 및 메뉴 이미지를 가공하는 기법 습득</li>
          <li>특정 데이터 소스(API)와 일반 정보(Google Search)를 상황에 맞게 구분하여 실행하는 툴 체인 설계</li>
        </ul>
      </div>
      <div>
        <div style="font-size: 13px; font-weight: 800; color: #5f3dc4; margin-bottom: 5px; text-transform: uppercase;">🎬 비즈니스 시나리오</div>
        <p style="font-size: 14px; color: #495057; line-height: 1.6; margin: 0;">
          본교 구성원의 미식 복지 향상을 위해, 오늘의 구내식당 정보와 주간 식단을 API를 통해 수집하고, 메인 메뉴의 스토리와 꿀팁을 구글에서 즉각 검색해 위트 있게 알려주는 <strong>'구내 식당 메뉴 알리미' 에이전트</strong>를 만듭니다.
        </p>
      </div>
    </div>
    <!-- Right Column: Tech & Outputs -->
    <div style="background: rgba(255, 255, 255, 0.6); padding: 20px; border-radius: 16px; border: 1px solid rgba(112, 72, 232, 0.15);">
      <div style="margin-bottom: 15px;">
        <div style="font-size: 12px; font-weight: 800; color: #5f3dc4; margin-bottom: 4px;">🛠️ 핵심 사용 기능</div>
        <div style="display: flex; flex-wrap: wrap; gap: 6px;">
          <span style="background: #fff; border: 1px solid #d0bfff; color: #5f3dc4; font-size: 12px; padding: 4px 10px; border-radius: 6px; font-weight: 600;">Custom MCP 연결</span>
          <span style="background: #fff; border: 1px solid #d0bfff; color: #5f3dc4; font-size: 12px; padding: 4px 10px; border-radius: 6px; font-weight: 600;">Agent Designer 빌더</span>
          <span style="background: #fff; border: 1px solid #d0bfff; color: #5f3dc4; font-size: 12px; padding: 4px 10px; border-radius: 6px; font-weight: 600;">시스템 Instructions 작성</span>
        </div>
      </div>
      <div>
        <div style="font-size: 12px; font-weight: 800; color: #5f3dc4; margin-bottom: 6px;">🎁 최종 기대 산출물</div>
        <div style="font-size: 14px; font-weight: 700; color: #212529; display: flex; align-items: center; gap: 8px;">
          🤖 '구내 식당 메뉴 알리미' 커스텀 에이전트 빌드
        </div>
        <div style="font-size: 12px; color: #6b7280; line-height: 1.4; margin-top: 4px;">
          오늘 메뉴뿐만 아니라 주간 일정 수집, 음식 유래 서치까지 연쇄 동작하는 고품질 마이크로 앱 완성
        </div>
      </div>
    </div>
  </div>
</div>

---

<!-- SLIDE 8: Module 6 (Chrome Integration) -->
<div style="
  background: linear-gradient(135deg, #f3f0ff 0%, #e8dbfc 100%);
  color: #7048e8;
  padding: 45px 40px;
  border-radius: 24px;
  box-shadow: 0 15px 35px rgba(112, 72, 232, 0.1);
  font-family: 'Inter', 'Noto Sans KR', sans-serif;
  margin-bottom: 50px;
  border: 1px solid #d0bfff;
">
  <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 20px;">
    <span style="background: #d0bfff; color: #5f3dc4; padding: 6px 16px; border-radius: 50px; font-size: 13px; font-weight: 800; letter-spacing: 0.5px;">실습 바 (06)</span>
    <span style="color: #5f3dc4; font-weight: 700; font-size: 14px;">⚡ 1초 만에 업무로 진입하는 빠른 생산성</span>
  </div>
  <h2 style="font-size: 28px; font-weight: 800; color: #5f3dc4; margin: 0 0 8px 0;">🌐 크롬 브라우저 주소창(Omnibar) 연동</h2>
  <div style="font-size: 16px; font-weight: 500; color: #6741d9; margin-bottom: 25px;">Gemini 사이트 이동 없이 브라우저 주소창에 검색하여 0초 만에 대답 얻기</div>

  <div style="display: grid; grid-template-columns: 1.2fr 1fr; gap: 30px;">
    <!-- Left Column: Purpose & Scenario -->
    <div>
      <div style="margin-bottom: 20px;">
        <div style="font-size: 13px; font-weight: 800; color: #5f3dc4; margin-bottom: 5px; text-transform: uppercase;">🎯 실습 목적</div>
        <ul style="font-size: 14px; color: #495057; line-height: 1.6; margin: 0; padding-left: 20px;">
          <li>사이트 주소를 직접 찾아 들어가야 하는 번거로운 행정 동선을 단숨에 제거</li>
          <li>기본 브라우저 Omnibar 엔진을 학교 커스텀 Gemini 엔터프라이즈로 다이렉트 매핑</li>
        </ul>
      </div>
      <div>
        <div style="font-size: 13px; font-weight: 800; color: #5f3dc4; margin-bottom: 5px; text-transform: uppercase;">🎬 비즈니스 시나리오</div>
        <p style="font-size: 14px; color: #495057; line-height: 1.6; margin: 0;">
          논문을 보거나 업무 행정 사이트를 보던 중, 리눅스 포트 프로세스를 급하게 제어해야 하거나 특정 서식을 검색해야 할 때 <strong>'ge [질문]'</strong>을 주소창에 입력해 즉각 지식을 확인합니다.
        </p>
      </div>
    </div>
    <!-- Right Column: Tech & Outputs -->
    <div style="background: rgba(255, 255, 255, 0.6); padding: 20px; border-radius: 16px; border: 1px solid rgba(112, 72, 232, 0.15);">
      <div style="margin-bottom: 15px;">
        <div style="font-size: 12px; font-weight: 800; color: #5f3dc4; margin-bottom: 4px;">🛠️ 핵심 사용 기능</div>
        <div style="display: flex; flex-wrap: wrap; gap: 6px;">
          <span style="background: #fff; border: 1px solid #d0bfff; color: #5f3dc4; font-size: 12px; padding: 4px 10px; border-radius: 6px; font-weight: 600;">Chrome Site Search 설정</span>
          <span style="background: #fff; border: 1px solid #d0bfff; color: #5f3dc4; font-size: 12px; padding: 4px 10px; border-radius: 6px; font-weight: 600;">%s 동적 검색 매핑</span>
          <span style="background: #fff; border: 1px solid #d0bfff; color: #5f3dc4; font-size: 12px; padding: 4px 10px; border-radius: 6px; font-weight: 600;">Omnibar 탭 키 트리거</span>
        </div>
      </div>
      <div>
        <div style="font-size: 12px; font-weight: 800; color: #5f3dc4; margin-bottom: 6px;">🎁 최종 기대 산출물</div>
        <div style="font-size: 14px; font-weight: 700; color: #212529; display: flex; align-items: center; gap: 8px;">
          ⚡ 브라우저 차원 통합 AI 생산성 확보
        </div>
        <div style="font-size: 12px; color: #6b7280; line-height: 1.4; margin-top: 4px;">
          언제든 "ge [스페이스바] 질문내용" 하나로 AI와의 즉각 협업 공간으로 다이렉트 런칭
        </div>
      </div>
    </div>
  </div>
</div>
