

https://pulsesolution.github.io


### 깃 최초 커밋

* 결과물

```
cd output
git init
git add .
git commit -m "first commit"
git remote add origin git@github.com:pulsesolution/pulsesolution.github.io.git
git push origin master --force
```

* 소스코드

```
git init
git add .
git commit -m "first commit"
git branch -m master source
git remote add origin git@github.com:pulsesolution/pulsesolution.github.io.git
git push origin source
```

### 깃 수정 커밋

* 결과물

```
cd output
git add -a
git commit -m "update"
git push origin master
```

* 소스코드

```
call pelpub.bat
git add -a
git commit -m "update"
git push origin source
```

### 깃 클론

```
git clone -b source git@github.com:pulsesolution/pulsesolution.github.io.git
```
