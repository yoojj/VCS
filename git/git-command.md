# git command

- [config](#config)
- [remote](#remote)



## config

```bash
# 터미널에서 명령어 색상 활성화
$ git config --global color.ui true
$ git config --global color.status auto
$ git config --global color.branch auto


# 알리야스
$ git config --global alias.co commit
$ git config --global alias.st status


# 인증 생략  
$ git config credential.helper store

# 일정 시간 동안 인증 생략
$ git config credential.helper 'cache --timeout=7200'


# global ignore
$ git config --global core.excludesfile ~/.gitignore_global
```



# remote


```bash
# 원격 저장소 등록
$ git remote add origin 주소

# 여러 원격 저장소 등록
$ git remote add 별명 주소

# 확인
$ git remote -v


# 저장소 주소 변경
$ git remote set-url origin 바뀔주소
$ git remote rename 주소 바뀔주소


# 저장소 제거
$ git remote remove 주소
```
