# upgraded 폴더 구조 및 설명

`upgraded` 폴더는 legacy 프로젝트의 모든 파일과 디렉터리를 최신 환경에서 작업할 수 있도록 복사한 구조입니다.

## 최상위 파일 및 폴더
- MANIFEST.in: 패키징에 포함할 파일 목록
- README.rst: 프로젝트 설명 파일
- distribute-0.6.10.tar.gz, distribute_setup.py: 레거시 배포 관련 파일
- setup.py: 프로젝트 설치 및 설정 스크립트
- docs/: 프로젝트 문서 및 Sphinx 관련 파일
- guachi/: 주요 Python 모듈 및 기능 구현
- guachi.egg-info/: 패키징 정보 및 메타데이터

## docs/
- build/: Sphinx 빌드 결과물 (doctrees, html)
- source/: Sphinx 문서 소스 (rst 파일, conf.py, _static)

## guachi/
- __init__.py, config.py, database.py: 핵심 모듈
- tests/: 단위 및 통합 테스트 스크립트

## guachi.egg-info/
- PKG-INFO, SOURCES.txt, dependency_links.txt, top_level.txt: 패키징 메타데이터

---

이 구조는 레거시 프로젝트를 최신 Python 환경에서 유지보수 및 업그레이드할 수 있도록 준비된 것입니다. 각 파일과 폴더는 원본과 동일하게 복사되었으며, 이후 업그레이드 작업을 이 디렉터리에서 진행하면 됩니다.