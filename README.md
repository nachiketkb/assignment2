CSCI 5828 <br/>

Homework 2 <br/>

Nachiket Bhagwat<br/>
Vipra Gupta<br/>
Chaitra Ramachandra<br/>

List of Commands - <br/>

Master Branch:Commit 0<br/>
1. mkdir assignment2 <br/>
2.cd assignment2 <br/>
3. git init <br/>
4. touch README.md</br>
5. vi README.md</br>
6. git status</br>

Master Branch:Commit 1</br>
7. git add README.md</br/>
8. git status</br/>
9. git commit -m "Commit #0"<br/>
10. git log --graph --abbrev-commit --decorate --date=relative --all<br/>
11. git branch<br/>
12. vi README.md<br/>
13. git status<br/>

Master Branch:Commit 2<br/>
14. git add README.md<br/>
15. git status<br/>
16. git commit -m "Commit #1:Parent Commit #0:Branch Master"<br/>
17. vi README.md<br/>
18. git status<br/>

Bug-fix Branch:Commit 3<br/>
19. git checkout -b bug-fix b777c70f0cda838e6a406882b000102bf83c1aa5<br/>
20. git branch<br/>
21. git log<br/>
22. vi README.md<br/>
23. git status<br/>

Bug-fix Branch:Commit 4<br/>
24. git add README.md<br/>
25. git commit -m "Commit #3:Parent Commit #0:Branch Bug-fix"<br/>
26. git log<br/>
27. vi README.md<br/>
28. git status<br/>

Bug-fix Branch: Commmit 5<br/>
26. git add README.md<br/>
27. git commit "Commit #4:Parent Commit #3:Branch Bug-fix"<br/>
28. git merge master<br/>
29. vi README.md<br/>
30. git status<br/>
