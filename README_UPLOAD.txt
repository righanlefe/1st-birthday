돌잔치 모바일 초대장 GitHub 업로드 안내

1) 이 폴더의 구조를 그대로 GitHub 저장소에 업로드하세요.

   index.html
   assets/images/1.jpg
   assets/images/2.jpg
   assets/images/map.png
   assets/images/gallery1.jpg ~ gallery11.JPG

2) GitHub Pages 설정
   - Repository > Settings > Pages
   - Source: Deploy from a branch
   - Branch: main / root 선택
   - 저장 후 안내되는 URL로 접속

3) 주의사항
   - 파일명 대소문자를 바꾸지 마세요. 특히 gallery11.JPG는 코드에서도 대문자 JPG로 연결되어 있습니다.
   - index.html 안에는 base64 이미지/오디오가 없으므로 GitHub 오류 가능성이 크게 줄었습니다.
   - 사진을 교체할 때는 같은 파일명으로 덮어쓰면 코드를 수정하지 않아도 됩니다.

[2026-05-07 수정 사항]
1. 히어로 페이지의 SCROLL 안내를 예전 스타일에 맞게 그라데이션 오버레이와 함께 복원했습니다.
2. 카카오맵/네이버지도 검색어를 '제주 제주시 연북로 222' 주소만 사용하도록 수정했습니다.
3. 첨부한 배경음악 파일을 assets/audio/feel-good-promo.mp3로 추가하고 자동재생을 시도하도록 적용했습니다.
   단, iPhone/Safari/Chrome 등 일부 모바일 브라우저는 정책상 소리 있는 자동재생을 차단할 수 있어 첫 화면 터치 후 즉시 재생되도록 보완했습니다.
