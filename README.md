# custom-git-server-nodejs

Command:
```bash
node index.js
```

Output:
```bash
node-git-server running at http://localhost:7005
```

On push to the custom git server
```bash
$ git push http://localhost:7005/beep master
Counting objects: 356, done.
Delta compression using up to 2 threads.
Compressing objects: 100% (133/133), done.
Writing objects: 100% (356/356), 46.20 KiB, done.
Total 356 (delta 210), reused 355 (delta 210)
remote:  
remote: Hey!
remote: Checkout these other repos:
remote: - test.git
remote:  
To http://localhost:7005/test
   77bb26e..22918d5  master -> master
```
