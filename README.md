# learn_git

1.Git Revert: quay trở lại một commit cụ thể bằng cách tạo ra một commit mới đảo ngược, các commit đằng sau commit bị đảo ngược sẽ không bị mất

2. Git reset: Đưa một branch về một commit cụ thể
   
    có 3 loại
   
        loại 1: git reset --soft <commit>: quay về commit cụ thể, các commit sau các commit đó vẫn ở trong stage changed
   
        loại 2: git reset --mixed <commit>: quay về commit cụ thể, các commit sau các commit đó vẫn ở trong unstage changed
   
        loại 3: git reset --hard <commit>: quay về commit cụ thể, các commit sau đó bị loại bỏ hoàn toàn
