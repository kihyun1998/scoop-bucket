# kihyun1998 Scoop bucket

[kihyun1998](https://github.com/kihyun1998)의 CLI 도구를 위한 [Scoop](https://scoop.sh) 버킷입니다.

## 사용법

```powershell
scoop bucket add kihyun1998 https://github.com/kihyun1998/scoop-bucket
scoop install jtic
```

업데이트:

```powershell
scoop update jtic
```

## 도구

| 이름 | 설명 |
|------|------|
| [`jtic`](https://github.com/kihyun1998/just-tic) | 오늘 git 커밋에서 추가/삭제한 줄 수(+/-)를 한 줄로 보여주는 CLI |

새 도구를 추가하려면 `bucket/`에 매니페스트 `.json`을 하나 더 두면 됩니다.
