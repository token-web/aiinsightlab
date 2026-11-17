자체 호스팅 글꼴 안내 (공식홈)
==============================

이 폴더의 글꼴 파일은 구글 폰트(https://fonts.google.com)에서 제공하는 오픈 글꼴을
웹용(woff2)으로 가공한 것입니다. 모두 SIL Open Font License 1.1 (OFL) 로 배포되며,
웹사이트에 사용하는 것은 무료입니다. 라이선스 전문은 같은 폴더의 OFL-*.txt 입니다.

[ 글꼴 ]
- Noto Sans KR   : Copyright 2014-2021 Adobe (http://www.adobe.com/), with Reserved Font Name 'Source'
                   -> OFL-notosanskr.txt
- Inter          : Copyright 2020 The Inter Project Authors (https://github.com/rsms/inter)
                   -> OFL-inter.txt

[ 가공 내용 ]
- 글꼴 원본: https://github.com/google/fonts (ofl/notosanskr, ofl/inter)
- 굵기 300/400/500/700 의 개별 글꼴로 만들고(Noto Sans KR), 필요한 글자만 추려 woff2 로 변환했습니다.
- noto-sans-kr-*-core.woff2 : 이 페이지에 실제로 쓰이는 글자만 담은 작은 파일 (평소에 이것만 내려받음)
- noto-sans-kr-*-ext.woff2  : 그 밖의 한글·기호 (새 글자가 생길 때만 자동으로 내려받음)
- inter-latin.woff2         : 영문·숫자용 (굵기 300~700 가변 글꼴)
- fonts.css                 : 위 파일을 연결하는 @font-face 설정

글꼴 파일은 직접 수정하지 마세요. 페이지 글을 크게 바꾸면 core 파일을 다시 만들어야 가장 가볍게 동작합니다.
