# TIL

### What will happen when we create Dockerfile

1. base image
   1. 근본
   2. Ubuntu, alpine, macos, etc....
2. layer...
3. another layer...

### Exercise

```dockerfile
# 베이스 이미지를 명시
FROM baseImage

# 추가적으로 필요한 파일들을 다운로드 받는다.
RUN ~~~

# 컨테이너 시작시 실행될 명령어를 명시해준다.
CMD ["excutable", "command"]
```



