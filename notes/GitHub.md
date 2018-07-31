# GitHub

### Git 시작하기

```bash
1. git init                     # git을 시작할게!
2. git add .                    # 변경된 모든 사항을 add하겠다
3. git commit -m "comment"      # 커밋 내용에 대한 메세지를 남겨줍니다
4. git remote add origin 주소    # repository의 주소를 복사/붙여넣기
5. git push -u origin master    # 깃헙 홈페이지에 push
```

### 두번째 commit

- `명령어 삼형제`만 적으면 됩니다

```bash
git add .     # 변경된 모든(.) 내용을 추가하겠다
git commit -m "comment"
git push -u origin master
```

### Github에 대한 정보

- 깃헙 홈페이지에서 `commits` 
  - 저장한 횟수 보여줌
  - 예전 버전 확인 가능
- 깃헙 홈페이지에서 `contributor`
  - 기여자와 얼마나 기여한지 보여줌
- `README.md`   repository에 대한 설명 
- `fork` : 내꺼에 넣어올수있음, 업데이트 반영은 안됨
- 멀캠에서 하던걸 집에서 하려면!

  ```
  터미널에서 git을 저장하려는 폴더 위치로 이동!
  해당 폴더에서 git clone 주소
  # 깃 홈페이지에서 clone or download 초록버튼 누르고 주소를 복사하면 편함
  ```

  - 멀캠에서 작업하고 `git push` 완료한 후, 집에서 `git pull`. 멀캠에서 업데이트한 내용을 받음
  - 그치만 push/pull 꼬일 수 있는데 어려우면 git clone을 새로 해봅니당

### Git errors
