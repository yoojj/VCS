# git error


## remote error

```bash
$ git push origin master

remote: Permission to [주소] denied to [사용자].
fatal: unable to access '주소': The requested URL returned error: 403
# 여러 계정 사용시 접근 문제


## credential 재설정
$ git credential reject
protocol=https
host=github.com


$ git credential fill
protocol=https
host=github.com
username=이메일
password=비밀번호
```



## with eclipse

```
~ cannot open git-receive-pack

1. eclipse git repositories 선택
2. remote - origin - configure push 선택
3. remote change 선택
4. 설정 정보 확인
```



[top](#)
