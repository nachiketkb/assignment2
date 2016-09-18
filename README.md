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

Bug-fix Branch:Commit 3<br/>
7. git checkout -b bug-fix b777c70f0cda838e6a406882b000102bf83c1aa5<br/>
8. git branch<br/>
9. git log<br/>
10. vi README.md<br/>
11. git status<br/>

Bug-fix Branch:Commit 4<br/>
12. git add README.md<br/>
13. git commit -m "Commit #3:Parent Commit #0:Branch Bug-fix"<br/>
14. git log<br/>
15. vi README.md<br/>
16. git status<br/>

Bug-fix-experimental: Commit 7<br/>
17. git checkout -b bug-fix-experimental f41a49c21b3c555efea5124b2fe463fc6d214fd8<br/>
18. git branch<br/>
19. vi README.md<br/>
20. git status<br/>

Bug-fix-experimental: Commit 8<br/>
21. git add README.md<br/>
22. git commit -m "Commit #7:Parent Commit #4:Branch Bug-fix-experimental"
23. vi README.md<br/>
24. git status<br/>

Bug-fix-experimental: Commit 9<br/>
25. git add README.md<br/>
26. git commit -m "Commit #8:Parent Commit #7:Branch Bug-fix-experimental"
27. vi README.md<br/>
28. git status<br/>