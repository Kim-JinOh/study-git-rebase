# GIT FLOW 전략
## Squash Merge
* 간단하게
```
git rebase -i
pick -> squash
```
* 되돌리기 (아직 연구 필요)
  * 직전 commit id 복사
```
git log
git rebase [직전 commit id]
```

