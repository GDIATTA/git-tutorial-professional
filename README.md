# git-tutorial-professional
Git usage in a professional environment

In this tutorial, we are going to see **Branchng**, **Merge** and **Feature Branch workflow** on git.

**------------------ Branching ---------------------** <br>
**Branching** means you diverge from the main line of development and continue to do work without messing with that main line. In many VCS tools, this is a somewhat expensive process, often requiring you to create a new copy of your source code directory, which can take a long time for large projects. <br>

We assume that you have several commits on your master branch as shown below.: <br>

![Capture d’écran 2024-09-07 021302](https://github.com/user-attachments/assets/d1487a67-e6fe-48bf-9a00-4ccaf2221f4f)

We will create another branch called **feature1** and then make several commits as follows. : <br>

![Capture d’écran 2024-09-07 022631](https://github.com/user-attachments/assets/4c106e0f-681e-46a4-862b-89215d12c9ad)

We assume there are bugs in your web app. How can you fix these bugs without disrupting/canceling your current work on the **feature1** branch? <br>

![Capture d’écran 2024-09-07 024043](https://github.com/user-attachments/assets/a46d1f2d-bd93-4fef-a8e7-42abec6e8096)
![Capture d’écran 2024-09-07 024109](https://github.com/user-attachments/assets/ef4da6db-6a25-4904-a05b-027d1a84a424)
![Capture d’écran 2024-09-07 024539](https://github.com/user-attachments/assets/173182d0-0b85-4ad2-a2f3-ea207f549fb8)

**----------------- Merge -------------------------------** <br>

We want **merge** these two branch : **master** and **feature1**. <br>

![Capture d’écran 2024-09-07 030605](https://github.com/user-attachments/assets/e47a788f-3b5a-4d3b-9b0f-a574403b6b7d)
![Capture d’écran 2024-09-07 025831](https://github.com/user-attachments/assets/4ec5a5be-921e-4138-a636-343c8004d53d)
![Capture d’écran 2024-09-07 030010](https://github.com/user-attachments/assets/94b0f49b-d3a2-4231-a56a-c8411be9aee4)
![Capture d’écran 2024-09-07 030122](https://github.com/user-attachments/assets/15909041-dc1f-489e-b9a0-47c0cfb47fb8)
![Capture d’écran 2024-09-07 030721](https://github.com/user-attachments/assets/b2b7688d-9b17-4b1a-825f-38b281f84ae7)


**---------------------------- Feature Branch workflow -----------------------**
