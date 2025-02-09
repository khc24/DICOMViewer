# DICOM Viewer (VTK 9.4 & GDCM 3.0)

![Project Image](https://github.com/khc24/DICOMViewer/tree/master/res/dicomviewer.png)) 

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
- 동일 그룹의 DICOM Volume 데이터 읽기 :사용자가 DICOM 트리에서 Volume을 더블 클릭하면 해당 Volume 데이터 로드
- Axal, Coronal, Sagittal 방향 슬라이스 이미지 생성 : 해당 Volume의 각 방향별 슬라이스 이미지 생성
- 스크롤바를 통한 슬라이스 탐색 : 사용자가 스크롤바를 움직이면 슬라이스 인덱스를 변경하며 탐색
- 3D Volume Rendering : 사용자가 미리 정의된 Volume Rendering 모드를 선택하면 3차원 렌더링 변경

---

## 🔧 설치 및 빌드 방법
### 1️⃣ 사전 준비
- Visual Studio 2022 및 CMake가 설치되어 있어야 합니다.
- `VTK 9.4.0` 및 `GDCM 3.0.24`을 사전 빌드합니다.

