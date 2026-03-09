Assignment 4

Tasks To Be Performed: 
1. Put master.txt on master branch, stage and commit 
2. Create 3 branches: public 1, public 2 and private 
3. Put public1.txt on public 1 branch, stage and commit 
4. Merge public 1 on master branch 
5. Merge public 2 on master branch 
6. Edit master.txt on private branch, stage and commit 
7. Now update branch public 1 and public 2 with new master code in private 
8. Also update new master code on master 
9. Finally update all the code on the private branch

solution
1. mkdir Assignment4
2. cd Assignment4
3. git init
4. nano master.txt
5. cat master.txt
6. git add master.txt
7. git commit -m "master.txt file is committed in master branch"
8. git branch
9. git branch public1
10. git branch public2
11. git branch private
12. git branch
13. git checkout public1
14. nano public1.txt
15. cat public1.txt
16. git add public1.txt
17. git commit -m "public1.txt file is added in public branch"
18. git checkout master
19. git merge public1
20. git merge public2
21. git checckout private
22. git checkout private
23. ls
24. nano master.txt
25. cat master.txt
26. git add master.txt
27. git commit -m "master.txt file text has beed edited"
28. nano master.txt
29. nano master.txt
30. git add master.txt
31. git commit m "master.txt file is edited"
32. git commit -m "master.txt file is edited"
33. git checkout public1
34. ls
35. cat master.txt
36. git checkout master
37. git merge private
38. cat master.txt
39. git checkout public1
40. cat master.txt
41. git merge master
42. cat master.txt
43. git checkout public2
44. git merge master
45. history
