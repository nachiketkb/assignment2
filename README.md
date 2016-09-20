CSCI 5828 <br/>

Homework 2 <br/>

Nachiket Bhagwat<br/>
Vipra Gupta<br/>
Chaitra Ramachandra<br/>

###List of Commands: <br/>

Master Branch: Commit 0<br/>
1. mkdir assignment2 <br/>
2. cd assignment2 <br/>
3. git init <br/>
4. touch README.md</br>
5. vi README.md</br>
6. git status</br>

Master Branch: Commit 1</br>
7. git add README.md</br/>
8. git status</br/>
9. git commit -m "Commit #0"<br/>
10. git log --graph --abbrev-commit --decorate --date=relative --all<br/>
11. git branch<br/>
12. vi README.md<br/>
13. git status<br/>

Master Branch: Commit 2<br/>
14. git add README.md<br/>
15. git status<br/>
16. git commit -m "Commit #1:Parent Commit #0:Branch Master"<br/>
17. vi README.md<br/>
18. git status<br/>

Bug-fix Branch: Commit 3<br/>
19. git checkout -b bug-fix b777c70f0cda838e6a406882b000102bf83c1aa5<br/>
20. git branch<br/>
21. git log<br/>
22. vi README.md<br/>
23. git status<br/>

Bug-fix Branch: Commit 4<br/>
24. git add README.md<br/>
25. git commit -m "Commit #3:Parent Commit #0:Branch Bug-fix"<br/>
26. git log<br/>
27. vi README.md<br/>
28. git status<br/>

Bug-fix Branch: Commmit 5<br/>
29. git add README.md<br/>
30. git commit -m "Commit #4:Parent Commit #3:Branch Bug-fix"<br/>
31. git merge master<br/>
32. vi README.md<br/>
33. git status<br/>

Bug-fix Branch: Commit 6<br/>
34. git add README.md<br/>
35. git commit -m "Commit #5:Parent Commit merged from #4 #2:Branch Bug-fix"<br/> 
Here we merge the branch bug-fix and master
36. git status<br/>
37. vi README.md<br/>
38. git status<br/>
19. git log<br/>
40. vi README.md<br/>
41. git status<br/>

Bug-fix-experimental: Commit 7<br/>
42. git checkout -b bug-fix-experimental f41a49c21b3c555efea5124b2fe463fc6d214fd8<br/>
43. git branch<br/>
44. vi README.md<br/>
45. git status<br/>

Bug-fix-experimental: Commit 8<br/>
46. git add README.md<br/>
47. git commit -m "Commit #7:Parent Commit #4:Branch Bug-fix-experimental"
48. vi README.md<br/>
49. git status<br/>

Bug-fix-experimental: Commit 9<br/>
50. git add README.md<br/>
51. git commit -m "Commit #8:Parent Commit #7:Branch Bug-fix-experimental"
52. vi README.md<br/>
53. git status<br/>

Bug-fix: Commit 11<br/>
54. git merge bug-fix-experimental<br/>
55. vi README.md<br/>
56. git status

Bug-fix: Commit 12<br/>
57. git add README.md<br/>
58. git commit -m "Commit #11:Parent Commit merged from #9 #2:Branch Bug-fix"<br/>
Here we merge the branch bug-fix and bug-fix-experimental
59. git status<br/>

Master Branch: Commit 10<br/>
60. git checkout master<br/>
61. git branch<br/>
62. vi README.md</br>
63. git status<br/>

Master Branch: Commit 13<br/>
64. git add README.md<br/>
65. git commit -m "Commit #12:Parent Commit #11:Branch Bug-fix"<br/>
66. git status<br/>
67. git checkout master<br/>
68. git merge bug-fix<br/>
69. vi README.md<br/>
70. git status<br/>

Master Branch: Commit 14<br/>
71. git add README.md<br/>
72. git commit -m "Commit #13:Parent Commit Merged #12 and #10:Branch Master"<br/>
Here we merge the branch bug-fix and master
73. git status<br/>
74. vi README.md<br/>
75. git status<br/>
76. git add README.md<br/>
77. git commit -m "Commit #14:Parent Commit #13:Branch Master"<br/>
No changes in README.md after Commit 14