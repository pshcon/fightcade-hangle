# fightcade-hangle
한글패치 - inGame

  1. Fightcade 완전히 종료
  2. zip 압축 풀기
  3. 그 안의 fcadefbneo.exe 파일을 자기 PC의 Fightcade\emulator\fbneo\ 폴더에 복사해서 기존 fcadefbneo.exe를 덮어쓰기
     (Fightcade 설치 경로 예: 문서\Fightcade\emulator\fbneo\ 또는 설치할 때 지정한 위치의 emulator\fbneo\ 폴더)
  4. 그대로 Fightcade 실행하면 끝 (다른 설정 건드릴 필요 없음)

## 안전성 확인

- SHA256: `25d47933e36d7464e733e429202808cd10f14991020a0386717073e2298bd4d1`
- VirusTotal 검사결과: [70여개 백신 전부 무결정(Undetected)](https://www.virustotal.com/gui/file/25d47933e36d7464e733e429202808cd10f14991020a0386717073e2298bd4d1)
- 소스코드 전체 공개(이 저장소) — 원본 [FBNeo](https://github.com/fightcadeorg/fightcade-fbneo)에 한글패치 코드만 추가한 것이며, 직접 빌드해서 검증 가능함

받은 zip의 exe 파일 SHA256 값이 위와 같은지 확인하려면 PowerShell에서:
```
certutil -hashfile fcadefbneo.exe SHA256
```
