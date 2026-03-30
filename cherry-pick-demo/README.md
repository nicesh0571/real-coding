# cherry-pick-demo

Git & GitHub 강의(2강) **마크다운 실습**용 README입니다.  
저장소 정보 요약, 마크다운 문법 예시를 한 파일에서 확인할 수 있습니다.

## 줄바꿈 (엔터만으로는 안 됨)

첫 번째 줄 끝에 공백을 두 칸 이상 넣으면  
이렇게 다음 줄로 넘어갑니다.

## 강조

강조하고 싶거나 중요한 내용: *기울이기*, _기울이기_, **굵게**, __굵게__, ~~취소선~~

## 순서 없는 목록

- 하이픈
* 별표
+ 플러스

## 순서 있는 목록

1. 첫 번째
2. 두 번째
3. 세 번째

## 체크박스 (GitHub에서 렌더)

VS Code 미리보기에서는 목록으로만 보일 수 있고, GitHub Issue·PR·README에서는 체크박스로 보입니다.

- [ ] 할 일
- [x] 완료한 일

## 링크

[마크다운 가이드 (GitHub Docs)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

## 이미지

![GitHub 로고 예시](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

## 코드 블록 (백틱 세 개 + 언어)

```python
def hello(name: str) -> str:
    return f"Hello, {name}"
```

## 인라인 코드

변수나 짧은 표현은 `git cherry-pick <commit>` 처럼 한 쌍의 백틱으로 감쌉니다.

## 구분선

아래는 `*` 세 개입니다.

***

아래는 `_` 세 개입니다.

___

아래는 `-` 세 개입니다.

---

## 표

| 명령 | 설명 |
| ------ | ------ |
| `git cherry-pick` | 특정 커밋만 현재 브랜치에 적용 |
| `git merge` | 브랜치 전체 이력을 합침 |

---

이 디렉터리는 강의 **cherry-pick 실습** 후 **README·마크다운** 파트를 따라 만든 예제 저장소입니다.
