# Git Assignment HeroVired

> **Note**
> Click on the headline below to access more details about the process

<details>

<summary style="font-size: 20px;">
<b>
<font size="+1">CalculatorPlus App Development</font>
</b>
</summary>

<!-- # CalculatorPlus App Development -->

Welcome to the development repository for CalculatorPlus, a Python application that provides basic arithmetic operations.

## Table of Contents

  - [Getting Started](#getting-started)
  - [Implementation](#implementation)
  - [Release V1.0](#release)
  - [Features](#features)
  - [Bug Fix](#bug-fix)
  - [Contributing](#contributing)
  - [Release V2.0](#release)


 ## Getting Started
 To get started with **CalculatorPlus** development, follow these steps:

1. Clone the repository :
    
    - Using gitbash :
    ```bash
    git clone https://github.com/abhijitganeshshinde/git_assignment_HeroVired.git
    ```
    ```bash
    cd git_assignment_HeroVired
    ```
    <details>
    <summary>For Example</summary>

    ![Image Alt Text](/Images/1.PNG)

    </details>
                
2. Create a new branch for development :
    ```bash
    git checkout -b dev
    ```
    <details>
    <summary>For Example</summary>

    ![Image Alt Text](/Images/2.PNG)

    </details>
3. Implement the square root feature in the Calculator class as specified in the assignment.

## Implementation

1. Create CalculatorPlus.py file.  
2. Add Your Code.
3. Check it's working or not.
4. Push the code in dev :
    ```bash
    git add .
    git commit -m "Added : Calculator Code"
    git push --set-upstream origin dev
    ```

## Release

To create a new release of CalculatorPlus :

1. Merge the dev branch into 'main' :
    ```bash
    git checkout main
    git merge dev
    git push
    ```
        
2. Click on Create a new release.
    <details>
    <summary>For Example</summary>

    ![Image Alt Text](/Images/58.png)

    </details>
3.  Create new tag:
    ```bash 
    v1.0
    ```
     <details>
    <summary>For Example</summary>

    ![Image Alt Text](/Images/11.PNG)

    </details>
5. Write your Release Title
6. Write your describe related to release and click on public release 
    <details>
    <summary>For Example</summary>

    ![Image Alt Text](/Images/60.PNG)
    ![Image Alt Text](/Images/12.PNG)

    </details>

## Features

To implement the square root feature and fix the bug, follow these steps:

1. Create new branch :
   ```bash
   git checkout -b feature/sqrt
   ```

2. Implement the square root feature :
    - Uncomment the square_root function in Calculator class.
    - Implement the sqrt function.

4. Test the application :
    ```bash
    python CalculatorPlus.py
    ```

## Bug Fix

If a critical bug is reported and you need to switch back to the dev branch to create fixes while keeping the **feature/sqrt** branch up-to-date:

1. Switch to the dev branch :
    ```bash
    git checkout dev
    ```        
2. Implement bug fixes.

3. Bug Fix :
    - In the divide function, replace with the following code :
    ```bash
        def divide(self, a, b):
            if b == 0:
                raise ValueError("Cannot divide by zero.")
            return a / b
    ```
    <details>
    <summary>For Example</summary>

    ![Image Alt Text](/Images/3.PNG)

    </details>

    
4. Switch back to the 'feature/sqrt' branch :
    ```bash
    git checkout feature/sqrt
    ```
        
4. Apply the latest changes from 'dev' :
    ```bash
    git merge dev
    ```

## Contributing

To contribute to the development of CalculatorPlus, follow these steps:

1. Add Your teammate 
   <details>
    <summary>For Example</summary>

    ![Image Alt Text](/Images/61.PNG)
    ![Image Alt Text](/Images/62.PNG)

    </details>

2. Create a new branch for your feature :
    ```bash
    git checkout -b feature/sqrt
    ``` 
3. Implement and test your feature.
    
4. Create a pull request targeting the dev branch.
    
5. Request a code review from a team member.
    
6. Make necessary improvements based on the code review feedback.
    
7. Once approved, merge your feature branch into 'dev'.

## Release

To create a new release of CalculatorPlus :

1. Merge the dev branch into 'main' :
    ```bash
    git checkout main
    git merge dev
    ```
        
2. Create a new release tag:
    git tag -a v2.0 -m "Version 2 Release"
        

3. Write your Release Title
4. Write your describe related to release and click on public release 
    <details>
    <summary>For Example</summary>

    ![Image Alt Text](/Images/63.png)

    </details>

</details>

---


<details>

<summary style="font-size: 20px;">
<b>
<font size="+1">Git Large File Storage (Git LFS)</font>
</b>
</summary>

<!-- # Git Large File Storage (Git LFS) -->

Welcome to the Git Assignment repository for demonstrating the usage of Git LFS (Large File Storage) for handling large binary files efficiently.

## Table of Contents
- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Integration Steps](#integration-steps)
- [Verifying Git LFS](#verifying-git-lfs)
- [Contributing](#contributing)

## Introduction

This repository showcases the integration of Git LFS to handle large binary files in a more efficient way. Git LFS allows us to manage and store large files separately, ensuring smoother version control and reduced repository size.

## Getting Started

To get started with Git LFS and test its functionality, follow the steps outlined below.

### Prerequisites

Before you begin, make sure you have Git LFS installed on your machine. If not, you can download and install it from the official website: [Git LFS](https://git-lfs.github.com/)

## Integration Steps

1. Clone the Repository:
   ```bash
   git clone https://github.com/abhijitganeshshinde/git_assignment_HeroVired.git
   cd git_assignment_HeroVired
   ```
2. Initialize Git LFS:
    ```bash
    git lfs install
    ```
    <details>
    <summary>For Example</summary>

    ![Image Alt Text](/Images/16.PNG)

    </details>

3. Create and Switch to a New Branch:
   ```bash
   git checkout -b lfs
   ```
   
4. Add a Large Binary File:
   - Upload a binary file larger than 200MB to the repository. For demonstration purposes, let's assume the file is named large-file.bin.

5. Configure Git LFS for the Large File:
    ```bash
    git lfs track "*.bin"
    ```
    <details>
    <summary>For Example</summary>

    ![Image Alt Text](/Images/17.PNG)

    </details>
6. Commit and Push:
    ```bash
    git add .
    git commit -m "Add large binary file using Git LFS"
    git push --set-upstream origin lfs
    ```
## Verifying Git LFS

1. On Another Machine:
   - Clone the repository on another machine using the following command:
    ```bash
        git clone https://github.com/abhijitganeshshinde/git_assignment_HeroVired.git
    ```
2. Verify the Large File:
   - After cloning, navigate to the repository directory and check that the large binary file (large-file.bin) is downloaded correctly and is stored as a pointer in Git LFS.

</details>

---

<details>

<summary style="font-size: 20px;">
<b>
<font size="+1">Geometry Calculator Development</font>
</b>
</summary>

<!-- # Geometry Calculator Development -->

Welcome to the development repository for the Geometry Calculator, a Python program that calculates the area of a circle and the area of a rectangle.

## Table of Contents
  - [Introduction](#introduction)
  - [Getting Started](#getting-started)
  - [Workflow Steps](#workflow-steps)
  - [Contributing](#contributing)
  - [Pull Requests](#pull-requests)

## Introduction

This repository contains the source code for the Geometry Calculator, a simple Python program that calculates the area of geometric shapes.

## Getting Started

To start contributing to the Geometry Calculator, follow these steps:

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/abhijitganeshshinde/git_assignment_HeroVired.git
   ```
   ```bash
   cd git_assignment_HeroVired
   ```
   ```bash
    git checkout geometry-calculator 
   ```
    <details>
    <summary>For Example</summary>

    ![Image Alt Text](/Images/17.PNG)

    </details>

## Workflow Steps
Follow these steps to work on the circle area and rectangle area features using Git stash:

1. #### Create a New Branch for Circle Area Feature:

    - Create a new branch named feature/circle-area to work on the circle area feature.
    ```bash
    git checkout -b feature/circle-area 
    ```
    <details>
    <summary>For Example</summary>

    ![Image Alt Text](/Images/17.PNG)

    </details>
2. #### Stash Changes for Circle Area Feature:

    - Before committing the changes, stash them using git stash to save the incomplete feature implementation.
     ```bash
    git stash save "Added : area of circle feature"
    ```
    - Verify that the working directory is clean using git status.
    - Check stash list:
     ```bash
    git stash list 
    ```
    <details>
    <summary>For Example</summary>

    ![Image Alt Text](/Images/30.PNG)
    ![Image Alt Text](/Images/31.PNG)
    ![Image Alt Text](/Images/32.PNG)

    </details>
3. #### Create a New Branch for Rectangle Area Feature:

    - Create a new branch named feature/rectangle-area to work on the rectangle area feature.
     ```bash
    git checkout -b feature/rectangle-area 
    ```
    <details>
    <summary>For Example</summary>

    ![Image Alt Text](/Images/33.PNG)

    </details>
4. #### Stash Changes for Rectangle Area Feature:

    - Before committing the changes, stash them using git stash to save the incomplete feature implementation.
    ```bash
    git stash save "Added : area of rectangle feature"
    ```
    - Verify that the working directory is clean using git status.
     <details>
    <summary>For Example</summary>

    ![Image Alt Text](/Images/36.PNG)
    ![Image Alt Text](/Images/37.PNG)

    </details>
5. #### Switch Back to Circle Area Branch:

    - Switch back to the feature/circle-area branch to continue working on the circle area feature.
    ```bash
    git checkout feature/circle-area
    ```
    - Check list of stash :
    ```bash
    git stash list
    ```
    - Retrieve the stashed changes using git stash pop or git stash apply.
    ```bash
    git stash apply "stash@{0}"
    ```
    - Complete the circle area feature implementation and save the changes.
    <details>
    <summary>For Example</summary>

    ![Image Alt Text](/Images/40.PNG)
    ![Image Alt Text](/Images/42.PNG)
    ![Image Alt Text](/Images/43.PNG)
    ![Image Alt Text](/Images/44.PNG)
    ![Image Alt Text](/Images/45.PNG)


    </details>
6. #### Commit and Push Circle Area Feature:

    - Commit your changes and push them to the remote branch using git commit and git push.
     ```bash
    git add .
    git commit -m "Added : Area of Circle"
    git push origin feature/circle-area
    ```
    <details>
    <summary>For Example</summary>

    ![Image Alt Text](/Images/46.PNG)
    ![Image Alt Text](/Images/47.PNG)
    ![Image Alt Text](/Images/48.PNG)

    </details>
7. #### Switch Back to Rectangle Area Branch:

    - Switch back to the feature/rectangle-area branch to continue working on the rectangle area feature.
    ```bash
    git checkout feature/rectangle-area
    ```
    - Check list of stash :
    ```bash
    git stash list
    ```
    - Retrieve the stashed changes using git stash pop or git stash apply.
    ```bash
    git stash apply "stash@{1}"
    ```
    - Complete the rectangle area feature implementation and save the changes.
    <details>
    <summary>For Example</summary>

    ![Image Alt Text](/Images/49.PNG)
    ![Image Alt Text](/Images/50.PNG)
    ![Image Alt Text](/Images/51.PNG)

    </details>
8. #### Commit and Push Rectangle Area Feature:

    - Commit your changes and push them to the remote branch using git commit and git push.
    ```bash
    git add .
    git commit -m "Added : Area of Rectangle"
    git push origin feature/rectangle-area
    ```
    <details>
    <summary>For Example</summary>

    ![Image Alt Text](/Images/54.PNG)

    </details>

## Contributing


### Pull Requests
   - Create a pull request for the feature/circle-area branch to the dev branch.
   - Create a pull request for the feature/rectangle-area branch to the dev branch.
### Review and Merge
   - After receiving approval, merge both pull requests into the dev branch.
   -  Reviewers will ensure the code is correct and follows project guidelines before merging into the main branch.

</details>

---
