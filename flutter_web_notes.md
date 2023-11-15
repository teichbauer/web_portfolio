# flutter-web-app dev
https://www.youtube.com/watch?v=YfNC0QiYNB8&list=PL0kMjh_O0eNcJDgS3Eglcc3hKeCA6a59K&index=2

- flutter create portfolio_website, getting a default app generated.
- `cd portfolio_website`, then do `code .`
- in vscode choose chrome(web-javascript) at the bottom
- in terminal: flutter build web
- go to github.com, sign-in(teichbauer/create a project named web_portfolio
- `cd web-apps\portfolio_website\build\web`
- `git add *`
- `git commit -m "first commit"`
- name the branch as main branch:
  `git branch -M main`
- connect to the remote
  `git remote add origin https://github.com/teichbauer/web_portfolio.git`
- `git push -u origin main`
  here I was asked to sign in (in the browser), and then it checked in all stuff

## server the page with python
- `cd portfolio_website\build\web`
- `python -m http.server 8009`
  then in a browser: http://localhost:8009/index.html