# 03. Git Remote

- `git remote` : Remote Repository 주소 등록 (여기서는 Github Repo)

  - `git remote add origin (주소)` : Remote Repo의 주소를 origin이라는 별칭으로 등록

  - `git remote -v` : 등록된 Remote 주소 확인

     ```bash
    origin  https://github.com/eunji7267/TIL.git (fetch)
    origin  https://github.com/eunji7267/TIL.git (push)
     ```

    - `fetch` : 데이터를 받아오는 주소

    - `push` : 데이터를 보내는 주소 (local에서 데이터를 보내는 주소)

      

- `git push (별칭) (브렌치이름)` : `별칭`으로 `브렌치`를 push(전송)

  - `git push origin main` : origin으로 main 브랜치를 전송

- `git clone (주소)` : 주소로부터 Repo 가져오기

- `git pull (별칭) (브렌치이름)` : `별칭`