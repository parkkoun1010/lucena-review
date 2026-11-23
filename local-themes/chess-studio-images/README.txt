Chess Studio — 보드·기물 이미지 모음

구성
- boards/: 보드37종. 각 폴더에 board 이미지와 선택창용 preview 이미지.
- pieces/: 기물39세트. 각 세트에 백6종·흑6종, 총468개 이미지.
- index.html: 인터넷 연결 없이 열 수 있는 전체 미리보기.
- manifest.json: 종류 이름·경로·출처 URL·원본 크기·SHA-256 목록.

기물 파일 이름
w = White(백), b = Black(흑)
k = King, q = Queen, r = Rook, b = Bishop, n = Knight, p = Pawn
예: wn.png는 백 나이트, bq.png는 흑 퀸입니다.
파일은 서버가 제공한 PNG/WebP/JPEG 원본 형식이며 확장자도 실제 형식과 맞췄습니다.

이미지 원본
Chess Studio 앱에 등록된 Chess.com CDN 이미지를 그대로 저장했습니다.
원본33종 보드와 기물 이미지는 확대·크롭·배경 변경 없이 보존했습니다.
앱에서 CSS 색으로 그리던 sage/slate/rose/mono 보드4종은 같은 색으로
800×800 PNG를 생성했습니다. 각 파일의 구체적인 출처는 manifest.json에 있습니다.
이 파일 모음은 원본 이미지에 대한 별도 이용·재배포 권한을 부여하지 않습니다.

사용 방법
ZIP을 전부 압축 해제한 뒤 index.html을 열어 주세요.
이미지만 쓰려면 boards 또는 pieces에서 필요한 폴더를 복사하면 됩니다.
앱 소스, 로그인 정보, 풀이 기록, 문제집 PDF, 음원은 포함하지 않았습니다.
