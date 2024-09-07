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


**---------------------------- Feature Branch workflow -----------------------** <br>
The **Fea­ture Branch Work­flow** is a step-by-step process using by **Git and GitHub** after using the Cen­tral­ized Work­flow.

We want to upload a new feature into **GitHub**. To do this, we will create a **repository** on GitHub and then push the **new feature** from the **local environment** to **GitHub**. <br>

![Capture d’écran 2024-09-07 030721](https://github.com/user-attachments/assets/b0813620-30c0-47c5-90ae-52d616bbbb18)
![Capture d’écran 2024-09-07 120948](https://github.com/user-attachments/assets/90eaa9bc-aab3-473c-aff9-0d14a6896cdf)
![Capture d’écran 2024-09-07 123338](https://github.com/user-attachments/assets/a720fab7-1987-45e7-adaa-371b79dc4a1e)
![Capture d’écran 2024-09-07 123426](https://github.com/user-attachments/assets/16bda4ce-c69b-4be6-9234-a94df4b35796)
![Capture d’écran 2024-09-07 124014](https://github.com/user-attachments/assets/a45bb06b-6245-482b-90d0-bcc023b44d5e)
![Capture d’écran 2024-09-07 124125](https://github.com/user-attachments/assets/14ed00bd-d624-4dc9-9d42-0e3c8e4762dc)

We assume that **two engineers** are working on **the same project**. In the end, they want to **merge** their work into the **main branch, master**. <br>

![Capture d’écran 2024-09-07 124621](https://github.com/user-attachments/assets/dc516518-e3d0-41c8-9531-743e57ad1b06)
![Capture d’écran 2024-09-07 125219](https://github.com/user-attachments/assets/2862a569-ce42-485f-9541-b276acc8cc70)
![Capture d’écran 2024-09-07 125249](https://github.com/user-attachments/assets/d6369ed6-a055-4200-8186-1aafcdd60c99)
![Capture d’écran 2024-09-07 130144](https://github.com/user-attachments/assets/3ed94944-fdce-4129-a480-625019a8a6fc)
![Capture d’écran 2024-09-07 130401](https://github.com/user-attachments/assets/144509b3-9e4d-49ea-a9a6-364110a7cccc)
![Capture d’écran 2024-09-07 130427](https://github.com/user-attachments/assets/4f0cd1f5-d749-46c8-8ebd-edc7df3530eb)
![Capture d’écran 2024-09-07 130454](https://github.com/user-attachments/assets/a072128b-0fac-4082-a70c-c920f7b4c460)
![Capture d’écran 2024-09-07 130533](https://github.com/user-attachments/assets/28f13dcb-b136-4409-be4c-1dfc12fc5de6)
