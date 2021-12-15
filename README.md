# Git Blog 제작 과정

## github repository 생성

1. 새로운 Repository 만들기
2. Repository 이름 설정

반드시 `username.github.io` 로 만들기

3. clone 하기 

`$ git clone 자신의 repository 주소`

## Jekyll 

1. 로컬에 Jekyll 설치 : 윈도우

윈도우는 RubyInstaller 다운로드 페이지에서 Ruby + Devkit 버전을 다운로드

`gem install jekyll bundler`

다운로드 후 위 명령어 입력

2. Jekyll 생성

`jekyll new . --force`

3. bundle install

`bundle install`

4. Jekyll을 로컬서버에 띄우기

`jekyll serve`

5. 원격에 push

`git add
git commit -m "commit message"
git push

## git Theme

[내가 사용한 테마](github.com/thelehhman/plainwhite-jekyll)

1. 선택한 테마 링크로 이동

2. 파일 가져오기

`git clone`

3. 전체 복사해서 내 github.io 폴더에 붙여넣기