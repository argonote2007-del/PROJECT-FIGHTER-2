# PROJECT FIGHTER TURN BATTLE

GitHub Pages 배포용 파일입니다.

## 배포 방법
1. GitHub 저장소의 최상위(root)에 `index.html`, `manifest.json`, `service-worker.js`, `icons` 폴더를 업로드합니다.
2. 저장소 Settings → Pages로 이동합니다.
3. Build and deployment에서 Deploy from a branch를 선택합니다.
4. Branch는 `main`, 폴더는 `/ (root)`를 선택하고 Save를 누릅니다.
5. 배포가 완료되면 표시되는 `https://계정이름.github.io/저장소이름/` 주소로 접속합니다.

## 참고
- 이 빌드에는 Firebase 익명 인증과 방 생성/방 코드 참가 대기실 기능이 포함되어 있습니다.
- 현재 버전은 온라인 방 접속 확인 단계이며, 팀 선택 및 실제 전투 행동의 실시간 동기화는 아직 구현되지 않았습니다.
- Firebase Realtime Database 보안 규칙이 올바르게 설정되어 있어야 방 생성/참가가 가능합니다.
- GitHub 저장소가 Public이면 게임 소스도 공개됩니다.
