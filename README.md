# UCI CS 169/268 Fall 2023

## About
This is all the files/work for CS 169. There were ***no quizzes for our quarter*** even though it is mentioned in the syllabus. ***Attendance was required***, an attendance sheet was passed during class where you had to sign. In addition, participation was graded on an honor system and was a check on the attendance sheet.

## Files
```
ics169
├── README.md
├── Syllabus169-268_FQ2023_V2.pdf
├── assignments (pdfs for the assignments)
├── final (python and pdf files for the final)
├── pdfs (pdf version of the jupyter notebook)
├── pictures (external picture to be included in notebook)
└── source (jupyter notebooks for each homework)
```

## Homework
- HW 0: env setup (python for undergrads and julia for grads)
- HW 1: Golden Section Method
- HW 2: Gradient Descent & Conjugate Gradient
- HW 3: Quasi-Newton Method 
- HW 4: Constrained Optimization
- HW 5: Final Overview

## Midterm
- 5 questions
    - 1: Classifying Optimization Methods 
        - he threw in others so you have to know what conditions must be met to use each algorithm
    - 2: Proofs for Steepest Descent
        - condition for direction vector $\vec{d}$
        - find the derivative of the line search function
        - something about the error after $n$ iterations
    - 3: Conjugate Gradients
        - what does it mean for 2 vectors to be conjugate
        - proof for finding $\beta_{k}$
        - proof for manipulating the equation for beta to remove the matrix from the numerator
        - (extra credit for undergrads required for grads: do the same process for the denominator)
    - 4: Newton's Method
        - formula to find the $x_{k+1}$
        - don't recall exactly but something about the hessian and why we want to use an approximation for it
    - 5: Grad Only (EC for undergrads)
        - idk what it was about
        
To study for the midterm just read the K&W book and understand the formulas/derivations behind each step. Look at the resources below for further supplement.

## Final
- The final was to work with a group to create a solve a constrained optimization problem of your choice
- There was a homework associated with the final which was simply to turn in a document with the group members name and what your group was working on.

## Resources
- [Conjugate Gradients](https://www.cs.cmu.edu/~quake-papers/painless-conjugate-gradient.pdf)
- [Newton's Method](https://www.youtube.com/watch?v=W7S94pq5Xuo)
- [General Videos](https://youtube.com/playlist?list=PLHAS_3-nESXV6XgW53wSkZHazVE7ZkHAV&si=DQfnwPV4GASaDekF)