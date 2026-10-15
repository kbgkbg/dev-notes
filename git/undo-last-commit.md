# Git: 마지막 커밋 되돌리기

`git reset --soft HEAD~1` 은 커밋만 취소하고 변경사항은 staged 상태로 남긴다. 이미 push 했다면 `git revert HEAD` 로 되돌리는 커밋을 새로 만드는 게 안전하다.
