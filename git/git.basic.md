## Git의 기초

### Git 저장소 만들기

#### 기존 디렉토리를 Git 저장소로 만들기

```sh
$ git init
```

- 이 명령은 .git이라는 하위 디렉토리를 만든다. .git 디렉토리에는 저장소에 필요한 뼈대 파일(Skeleton)이 들어 있다. 이 명령만으로는 아직 프로젝트의 어떤 파일도 관리하지 않는다.
- Git 저장소를 삭제하려면 단지 .git이라는 디렉토리를 지우면 된다.

#### 기존 저장소를 Clone 하기

```sh
$ git clone https://github.com/liggit2/libgit2
```
