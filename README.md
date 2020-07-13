# .github.io
    - 참고 https://github.com/iRaul/creative-portfolios

    - 계정명.github.id repository 생성
        - README.md 필수

    - node 및 git 설치 필요
        - npm i -g hexo-cli
        - hexo init 폴더명
        - cd 폴더명
        - npm i
        - hexo server
        - http://localhost:4000
        - theme https://hexo.io/themes
        - icarus https://github.com/ppoffice/hexo-theme-icarus
        - 테마 다운 후 압축 해제 -> themes 폴더 하위로 잘라내기 -> _config.yml 에서 theme 값 변경(theme : icarus)
        - 새 페이지 추가 -> hexo new page 페이지명
        - _config.yml 수정(type, repo, branch)

    - 배포
        - npm i hexo-deployer-git
        - 정적리소스 생성 : hexo generate
        - 배포 : hexo deploy
        - 리소스 삭제 : hexo clean
        - 리소스 생성+배포 : hexo d -g