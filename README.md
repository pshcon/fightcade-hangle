# fightcade-hangle
한글패치 - inGame

## 설치법
  1. Fightcade 완전히 종료
  2. 오른쪽 Releases에서 최신 버전의 fcadefbneo_.zip 받아서 압축 풀기
  3. Fightcade\emulator\fbneo 폴더의 fcadefbneo.exe를 새로 받은 파일로 교체
  4. Fightcade 재실행

## 주요기능
- 인게임 채팅에서 한글 입력/표시 지원 (채팅창 열면 자동으로 한글모드로 시작)
- 상대방도 이 패치를 쓰는지 자동 감지해서 채팅창에 표시
- 가끔 게임이 멈춰서 재부팅해야 했던 문제 해결

## 바이러스 검사결과
- SHA256: `e0a12dd8d37632b7a42358e98f155e76cde25293457cf1673a8253aee99b981c`
- 소스코드 전체 공개 ([source 브랜치](https://github.com/seonghonge/fightcade-hangle/tree/source)) — 원본 [FBNeo](https://github.com/fightcadeorg/fightcade-fbneo)에 한글패치 코드만 추가한 것이며, 직접 빌드해서 검증 가능함

받은 zip의 exe 파일 SHA256 값이 위와 같은지 확인하려면 PowerShell에서:
```
certutil -hashfile fcadefbneo.exe SHA256
```
