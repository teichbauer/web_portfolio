# flutter-web-app dev
## tutorial source
https://www.youtube.com/watch?v=YfNC0QiYNB8&list=PL0kMjh_O0eNcJDgS3Eglcc3hKeCA6a59K&index=2

## create the app
getting a default app generated.
```
flutter create portfolio_website
```
`cd portfolio_website`, then do `code .`
Here `portfolio_website` is the ROOT

## setting up

- in vscode choose chrome(web-javascript) at the bottom
- in terminal, under ROOT: 
```
flutter build web
```

## get it into github
- go to github.com, sign-in(teichbauer/create a project named web_portfolio
- `cd web-apps\portfolio_website\build\web`
- `gir init`
- `git add *`
- `git commit -m "first commit"`
- name the branch as main branch:
  `git branch -M main`
- connect to the remote
  `git remote add origin https://github.com/teichbauer/web_portfolio.git`
- `git push -u origin main`
  here I was asked to sign in (in the browser), and then it checked in all stuff

## serve the page with python
```
cd portfolio_website\build\web
```
```
python -m http.server 8009
```
then in a browser: http://localhost:8009/index.html