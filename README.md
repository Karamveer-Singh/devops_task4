# devops_task4

Build a Version-Controlled DevOps Project with Git

By Gur Sahib Ji's grace tried to solve above task initializing git into local system, then created a repository on Github, which later added to local system as a remote repository. master branch was named as main, 2 branches were created, named dev and feature branch. New files were separately added to them. Plus some files were added to main branch , later dev branch and feature branch were pushed to remote repository where pull requests were created and then merge operation  were performed. Later on local system  main branch was pulled from remote to local and merge operations were performed after  adding new changes to dev and feature branches. Later, .gitignore file was added including its content and atgs were added at the end. Tried to add all screenshots of task.

Workflow:

1. On Local system, directory named "devops_task4" is created using:

   mkdir devops_task4

2. cd devops_task4
3. ls
4. ls -a
5. Initialize git using:
   
   git init

6. ls -a
7. echo "# devops_task4" >> README.md
8. For checking status:
   
   git status

9. For checking current branch, we are on:
   
   git branch

10. Adding changes to staged area:

   git add README.md

11. git status
12. git commit -m "first commit"
13. git branch
14. Changing the branch name:

    git branch -M main
 
15. git branch
16. Firstly created a repository named "devops_task4" on github, now adding remote repository to local using:
  
    git remote add origin https://github.com/Karamveer-Singh/devops_task4.git

17. Checking connected remote repositories on local using:
  
    git remote -v

18. Pushing local commits to remote connected repository using:

    git push -u origin main

19. git branch
20. Creating new branch named "dev":

    git checkout -b dev
21. git branch
22. Checking commits as log using:
   
    git log

23. Moving to "main" branch using:

    git checkout main

24. git branch
25. git log
26. Moving to "dev" branch using:

    git checkout dev
27. git status
28. ls
29. Creating a new file named "file1" on dev branch using:
   
    nano file1

30. git status
31. git add .
32. git commit -m "added file1"
33. git log
34. git branch
35. git checkout main
36. git log
37. git checkout dev
38. Adding one more file into dev branch using:
 
    nano file2

39. git status
40. git add .
41. git commit -m "added file2"
42. git log
43. git branch
44. git status
45. git checkout main
46. Adding a new file named "file3" into main branch using:

    nano file3

47. git status
48. git add .
49. git commit -m "added file3 in main branch"
50. git status
51. git log
52. git branch
53. Creating a new branch named "feature" from "main" branch using:

    git checkout -b feature

54. git branch
55. git log
56. ls
57. Creating file4 on feature branch using:
  
    nano file4

58. git status
59. git add .
60. git commit -m "added file4 in feature branch"
61. git log
62. git checkout main
63. git log
64. git branch
65. git checkout feature
66. git diff main
67. ls
68. Pushing feature branch onto connected remote repository using:
   
    git push origin feature

# "Pull request was created on github and feature branch was merged with main branch of remote repository "devops_task4" "

But on local system there are still differences between feature and main branch as they are not merged on local system.
Now,

69. git diff main
70. git branch
71. git checkout dev
72. git diff main
73. ls
74. git push origin dev
 
# "Pull request was created on github and dev  branch was merged with main branch of remote repository "devops_task4"

But on local system there are still differences between dev and main branch as they are not merged on local system.
Now

75. git diff main
76. git checkout main
77. ls
78. Pulling the main branch on local system using:

    git pull origin main
  
79. ls
80. git log
81. git branch
82. ls
83. git checkout feature
84. ls
85. git checkout dev
86. ls
87. git branch
88. git diff main
89. git checkout feature
90. git diff main
91. ls
92. Merging feature branch into main branch on local system using:
   
    git merge main

93. ls
94. git log
95. git branch
96. Adding text into file4 on feature branch to learn merge conflicts:
   
    nano file4

97. git status
98. git add .
99. git commit -m "for learning purpose"
100. git checkout dev
101. Adding text into file4 on dev branch to learn merge conflicts:

    nano file4

102. git status
103. git add .
104. Making commit on dev branch  on local system:

    git commit -m "for learning merge conflicts"

105. Checking conflicts between file4 on dev and feature branch:

    git diff feature

106. Trying to merge dev and feature branch:

    git merge feature

107. Trying to resolve conflict manually in file4 on dev branch:
 
    nano file4
 
108. git status
109. git add .
110. git commit -m "tried to resolve merge conflict mannually"
111. git merge feature
112. git checkout feature
113. nano file4
114. git diff dev
115. cat file4
116. git checkout dev
117. cat file4
118. git checkout feature
119. git diff dev 
120. git merge dev
121. cat file4
122. git log
123. git branch
124. git checkout main
125. git diff feature
126. git merge feature
127. cat file4
128. git log
129. git branch
130. touch .gitignore
131. ls
132. touch file5 file6
133. ls
134. Added name file5 and file6 into .gitignore file:

    nano .gitignore 

135. git status
136. git add .
137. git commit  -m "learning about ,gitignore"
138. git log
139. git push origin main
140. git status
141. git tag -a v1.4 
142. git status
143. git show v1.4
144. git log
145. git tag
146. git show v1.4
147. git tag -l "v1.8.5*"
148. Annotated tag used:

    git tag -a v1.5 -m "new version tag"

149. git tag show v1.5
150. git show v1.5
151. git tag v1.4-1w
152. git tag
153. git show
154. touch Document
155. git branch
156. nano Document
157. git status
158. git add .
159. git commit -m "devops_task4"
160. git pull origin main
161. git diff
162. nano README.md 
163. git diff
164. git add .
165. git commit -m "conflict resolved"
166. git status
167. git push origin main

thanks 
