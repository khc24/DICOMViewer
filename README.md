# DICOM Viewer (VTK 9.4 & GDCM 3.0)

![Project Image](YOUR_IMAGE_PATH)

## 📌 프로젝트 개요
본 프로젝트는 **VTK 9.4.0**과 **GDCM 3.0.24**을 활용하여 DICOM 데이터를 로드하고 3D 볼륨 렌더링을 수행하는 C++ 기반 뷰어입니다.  
Visual Studio 2022에서 개발되었으며, 의료 영상 데이터를 효율적으로 시각화하는 기능을 제공합니다.

---

## 🛠️ 사용 기술 및 라이브러리
- **언어**: C++  
- **라이브러리**:
  - [VTK 9.4.0](https://vtk.org/)
  - [GDCM 3.0.24](http://gdcm.sourceforge.net/)
- **개발 환경**:
  - Visual Studio 2022
  - CMake

---

## ✨ 주요 기능
- DICOM 파일(.dcm) 불러오기 및 3D 볼륨 렌더링
- 슬라이서 기능: CT/MRI 단층 이미지 탐색
- 기본적인 윈도우 레벨 조정 지원
- 인터랙티브 카메라 조작 (회전, 확대, 이동)
- 다중 뷰 모드 (Axial, Coronal, Sagittal)

---

## 🔧 설치 및 빌드 방법
### 1️⃣ 사전 준비
- Visual Studio 2022 및 CMake가 설치되어 있어야 합니다.
- `VTK 9.4.0` 및 `GDCM 3.0.24`을 사전 빌드합니다.

