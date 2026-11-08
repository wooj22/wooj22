# Hi, I'm 양우정 (UJeong Yang) 👋

**엔진 밑단부터 게임플레이까지 만드는 게임 클라이언트 프로그래머입니다.**

컴포넌트 기반 2D 자체 엔진과 DX11 3D 렌더러를 직접 구현해 팀 프로젝트에 적용했고,
Unreal Engine 5로 소울라이크 전투 · UI · 연출 · CI/CD를 담당했습니다.

- 📒 **Portfolio** : [Notion](https://app.notion.com/p/wooj22/Game-Client-Programmer-Portfolio-4126c921e70a80b9b4a0c44cf54edeaf)
- ✉️ **Email** : wooje222@gmail.com
- ✍️ **Blog** : [양양의 게임개발](https://wooj22.tistory.com/)
- ▶️ **YouTube** : [양우정](https://www.youtube.com/@%EC%96%91%EC%9A%B0%EC%A0%95-g8v/videos)

---

### 🛠️ Tech Stack

**Languages**
![C++](badges/cpp.svg)
![HLSL](badges/hlsl.svg)
![C#](badges/csharp.svg)

**Engines & Graphics**
![Unreal Engine 5](badges/unreal-engine-5.svg)
![Unity](badges/unity.svg)
![Custom Engine](badges/custom-engine.svg)
![DirectX 11](badges/directx-11.svg)
![Direct2D](badges/direct2d.svg)

**Libraries**
![Assimp](badges/assimp.svg)
![ImGui](badges/imgui.svg)
![FMOD](badges/fmod.svg)
![MediaPipe](badges/mediapipe.svg)

**Tools & CI/CD**
![Visual Studio](badges/visual-studio.svg)
![RenderDoc](badges/renderdoc.svg)
![Git](badges/git.svg)
![SVN](badges/svn.svg)
![Jenkins](badges/jenkins.svg)
![Claude Code](badges/claude-code.svg)

---

### 🎮 Projects

> AI 분석 기여도는 git 기록을 AI로 분석해 정리했습니다. **상** 해당 영역을 주도 · 전담 / **중** 팀원과 분담 / **하** 일부 지원

#### ⚔️ Re : Volition
- **링크** : 비공개 팀 레포
- **장르** : 3D 타임리프 소울라이크 액션 · 팀 프로젝트 (진행 중)
- **기술** : Unreal Engine 5 · C++ · CommonUI · Jenkins
- **담당** : 전투 HFSM (공격 · 회피 · 패링 · 가드, 입력 예약 / 캔슬) · 신성 흡수 증강 시스템 · CommonUI 인게임 UI · 캐릭터 연출 / VFX · 타임리프 PostProcess 셰이더 · Jenkins CI/CD
- **AI 분석 기여도** : 상 · 플레이어 전투 · 연출 · 빌드 파이프라인을 주도하고, 인게임 UI 구조를 설계

#### 🍚 제사상
- **링크** : [MoonSun-v/JesaSang](https://github.com/MoonSun-v/JesaSang)
- **장르** : 3D 잠입 스릴러 요리 퍼즐 · 팀 프로젝트
- **기술** : C++ · DirectX 11 · HLSL · 자체 엔진
- **담당** : 렌더링 전담 (Deferred + Forward Hybrid, PBR · IBL, Light Volume 다중 광원 최적화 181ms → 16ms, Decal) · 플레이어 FSM · 조리 미니게임 · 카메라
- **AI 분석 기여도** : 상 · 팀 엔진의 렌더링 파트를 전담하며 그래픽스 기반을 책임지고, 주요 클라이언트 시스템 구현

#### 🔆 DX11 3D Renderer
- **링크** : [wooj22/DirectX3D11_Study](https://github.com/wooj22/DirectX3D11_Study)
- **장르** : 3D 렌더링 파이프라인 · 개인 프로젝트
- **기술** : C++ · DirectX 11 · HLSL · Assimp · ImGui · RenderDoc
- **담당** : Deferred + Forward Hybrid · Light Volume / Stencil · PBR · IBL · Shadow Mapping (PCF) · HDR · Bloom · Decal · Particle
- **AI 분석 기여도** : 상 · 설계부터 구현까지 단독 진행

#### 🌘 Eclipse
- **링크** : [wooj22/Eclipse](https://github.com/wooj22/Eclipse)
- **장르** : 2D 사이드뷰 웨이브 디펜스 액션 플랫포머 · 팀 프로젝트
- **기술** : C++ · Direct2D · FMOD · 자체 엔진
- **담당** : 엔진 전담 (One-Way 플랫폼 Collision, CCD 터널링 방지, 런타임 오브젝트 생성 크래시 해결) · 혼 충돌 연쇄반응 · 보스 탄막 패턴 · 연출
- **AI 분석 기여도** : 상 · 사전 제작한 엔진을 팀 프로젝트에 적용하고, 개발 기간 동안 엔진 확장과 유지보수를 전담

#### 🦾 Friend Engine
- **링크** : [wooj22/Friend_Engine](https://github.com/wooj22/Friend_Engine)
- **장르** : 2D 게임 엔진 · 개인 프로젝트
- **기술** : C++ · Direct2D · FMOD
- **담당** : GameObject-Component 구조 · 고정 타임스텝 Game Loop · Sweep and Prune Physics · FSM Animation · Resource Manager
- **AI 분석 기여도** : 상 · 설계부터 구현까지 단독 진행

#### 🎡 Midnight Carnival
- **링크** : [wooj22/MidnightCarnival](https://github.com/wooj22/MidnightCarnival)
- **장르** : LiDAR · 다면 프로젝션 XR 테마파크 체험 콘텐츠 · 산학 협력 (SIGGRAPH Asia 2024 전시)
- **기술** : Unity · C# · LiDAR · OSC · Spout · Resolume
- **담당** : LiDAR 센서 실시간 인터랙션 · 다면 실시간 송출 · 전시장별 플랫폼 전환과 캘리브레이션 · 어트랙션 게임
- **AI 분석 기여도** : 상 · 센서 입력부터 다면 송출까지 파이프라인을 맡아, 전시 현장 세팅과 운영까지 대응

#### 🏋️ HT-Monster Hunter
- **링크** : [wooj22/HT-MonsterHunter](https://github.com/wooj22/HT-MonsterHunter)
- **장르** : 모션 인식 AR 홈트레이닝 게임 · 졸업 프로젝트 (KGDcon 2024 전시)
- **기술** : Unity · C# · MediaPipe · Python
- **담당** : MediaPipe 포즈 데이터 Unity 연동 · 관절 각도 기반 동작 판정 · 운동 루틴과 몬스터 전투
- **AI 분석 기여도** : 중 · 포즈 인식 연동과 동작 판정 로직을 중심으로 게임 콘텐츠 구현

#### 🪞 MirrorFall
- **링크** : [wooj22/MirrorFall](https://github.com/wooj22/MirrorFall)
- **장르** : 2.5D 쿼터뷰 심리 호러 퍼즐 · 팀 프로젝트
- **기술** : Unity · C#
- **담당** : 플레이어 FSM · 거울 조각 퍼즐 · FSM Step 튜토리얼 · 2.5D Y-Sort 정렬 · 인벤토리 / 아이템
- **AI 분석 기여도** : 상 · 플레이어 · 튜토리얼 · 게임 흐름 등 핵심 플레이 루프를 주로 담당

#### 👻 TRUTH TRAIL : exorcism of deception
- **링크** : [TRUTH-TRAIL](https://github.com/TRUTH-TRAIL) · [Steam](https://store.steampowered.com/app/3001150/TRUTH_TRAIL__exorcism_of_deception/)
- **장르** : 공포 · 팀 프로젝트 (Steam 무료 출시)
- **기술** : Unity · C#
- **담당** : 기획 · PM 전담 · 후반부 개발 지원
- **AI 분석 기여도** : 하 (개발) · 기획과 일정 관리를 맡아, 팀 개편을 거쳐 Steam 출시까지 함께 완주

---

### 🏆 Exhibitions & Papers
- SIGGRAPH Asia 2024 도쿄 국제 포럼 전시 — *Midnight Carnival*
- FutureGround 현대백화점 인천 중동점 전시 — *Midnight Carnival*
- KGDcon 2024 킨텍스 전시 — *HT-Monster Hunter*
- 논문 「미디어 파이프 기술을 이용한 홈트레이닝용 피트니스 게임」
- 논문 「XR기술을 활용한 4면 테마파크 실감 미디어 콘텐츠 개발 연구: 'Midnight Carnival'을 중심으로」

### 🎓 Education
- 게임인재원 7기 프로그래밍 과정 (2025 – 2027)
- 서울여자대학교 소프트웨어융합학과 졸업 (2020 – 2026)
