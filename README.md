# vscode_utils
vscode 세팅에 필요한 여러가지들

## 파일탭 여러줄(multiple lines)
File 메뉴 > Preferences > Settings(Ctrl+,) > wrap tabs
## 단축키
ctrl + shift + l : 단어선택하고 누르면 같은 단어 전체 변경 가능

# vscode에서 터미널에서 모든 변경사항 git remote에 반영
```sh
git add *
git commit -m "코멘트 쓸내용 적기"
git pull # remote repo에 바뀐내용이 있으면 변경사항을 local repo에 반영먼저 시킨다.
git push
```