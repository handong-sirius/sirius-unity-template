# 🎮 SIRIUS Unity Project Template

시리우스 학회원들이 **Unity 프로젝트를 시작할 때** 사용하는 **공용 템플릿**입니다.  
프로젝트 시작 전, 이 템플릿을 복사해서 사용하세요.  
(깃허브 **"Use this template"** 기능 활용 권장)

---

## ✅ 목적
- 프로젝트 초기 세팅 시간을 줄이고, **통일된 폴더 구조**를 유지
- **공용 유틸/코드**를 쉽게 재사용
- 학회원 간 협업 시 **충돌 및 관리 편의성** 향상

---

## ✅ Unity Version
- **2022.3.XXf1 (LTS)**  
  (모든 프로젝트는 이 버전을 기본으로 합니다.)

---

## 📁 폴더 구조
Assets/<br>
 ├─ __Project/      &nbsp;&nbsp;&nbsp;&nbsp;    # (핵심 게임 로직 & 프로젝트 고유 요소)<br>
 │   ├─ Scripts/    &nbsp;&nbsp;&nbsp;&nbsp;    # 게임 핵심 스크립트<br>
 │   ├─ Scenes/     &nbsp;&nbsp;&nbsp;&nbsp;    # 씬 (메인, 테스트, 샘플 등)<br>
 │   ├─ Prefabs/    &nbsp;&nbsp;&nbsp;&nbsp;    # 프로젝트에서 쓰이는 주요 프리팹<br>
 │   └─ UI/         &nbsp;&nbsp;&nbsp;&nbsp;    # UI 캔버스, 버튼, 매니저 등<br>
 │<br>
 ├─ _Art/                    # 그래픽 관련 (외부 리소스 + 직접 제작)<br>
 │   ├─ Sprites/             # 2D 이미지 (PNG 등)<br>
 │   ├─ Models/              # 3D 모델 (FBX 등)<br>
 │   └─ Materials/           # 머티리얼 및 셰이더<br>
 │
 ├─ _Audio/                  # 사운드 관련<br>
 │   ├─ Music/               # 배경음악<br>
 │   └─ SFX/                 # 효과음<br>
 │<br>
 ├─ _Animation/              # 애니메이션 관련<br>
 │   ├─ Controllers/         # 애니메이터 컨트롤러<br>
 │   └─ Clips/               # 애니메이션 클립<br>
 │<br>
 ├─ Plugins/                # 외부 플러그인 (에셋 스토어 등)<br>
 │<br>
 ├─ Tests/                  # 테스트용 씬 & 샘플 코드<br>
 │<br>
 └─ Docs/                   # 문서 (README, 가이드, 참고용 이미지)<br>

