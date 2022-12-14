# Secureum X Diligence bootcamp: Writing Scribble Specifications and Using Diligence Fuzzing (November 3–9, 2022)

This bootcamp is a collaboration between [Secureum](https://www.secureum.xyz) and [ConsenSys Diligence](https://consensys.net/diligence). We will teach participants how to specify custom correctness properties for smart contracts using our [Scribble language](https://consensys.net/diligence/scribble). We will also introduce them to our [Diligence Fuzzing service](https://consensys.net/diligence/fuzzing) (DF) and show them how to use fuzzing to find property violations automatically.


## Schedule

### Day 1 (November 3, 2022)

- **course kick-off and intro lecture to Scribble (14:30-15:15 CET on [Google Meet](meet.google.com/cbf-pvku-yfg))**
  1) introduce course website with exercises, resources, etc.
  2) provides an overview of Scribble and key language features
  3) introduces initial Scribble exercises


### Day 2 (November 4 2022)

- **advanced Scribble lecture (14:30-15:15 CET on [Google Meet](meet.google.com/cbf-pvku-yfg))**
  1) introduces more advanced Scribble features (e.g., if_updated, quantifiers, and assert/let)
  2) introduces additional Scribble exercises

- **office hour (15:15-16:15 CET on [Google Meet](meet.google.com/cbf-pvku-yfg))**: get help with Scribble exercises and discuss solutions


### Day 3 (November 7, 2022)

- **intro lecture to Diligence Fuzzing (14:30-15:15 CET on [Google Meet](meet.google.com/cbf-pvku-yfg))**
  1) provides an overview of DF and shows how to fuzz a simple contract
  2) introduces initial DF exercises

- **office hour (15:15-16:15 CET on [Google Meet](meet.google.com/cbf-pvku-yfg))**: get help with Scribble/DF exercises and discuss solutions


### Day 4 (November 8, 2022)

- **advanced Diligence Fuzzing lecture (14:30-15:15 CET on [Google Meet](meet.google.com/cbf-pvku-yfg))**
  1) introduces more advanced DF features (e.g., fuzzing lessons)
  2) provides an overview of what's going on under the hood in our Harvey fuzzer
  3) introduces additional fuzzing exercises

- **office hour (15:15-16:15 CET on [Google Meet](meet.google.com/cbf-pvku-yfg))**: get help with Scribble/DF exercises and discuss solutions


### Day 5 (November 9, 2022)

- **office hour (15:15-16:15 CET on [Google Meet](meet.google.com/cbf-pvku-yfg))**: get help with Scribble/DF exercises and discuss solutions


## Instructors

- [Dimitar Bounov](https://github.com/cd1m0) (Dimo#1001)
- [Joran Honig](https://joranhonig.nl) (walker#3905)
- [Valentin Wüstholz](http://www.wuestholz.com) (wuestholz#3558)


## Resources/Links

### Lectures

#### Day 1

- [recording](https://drive.google.com/file/d/1umkVxO3xX6Vu6cslWJ5xEZCXW7jQCC9o/view?usp=sharing)
- [slides](https://github.com/ConsenSys/secureum-diligence-bootcamp/blob/main/day1/lecture1.pdf)


#### Day 2

- [recording](https://drive.google.com/file/d/1DJpwduUkgO5gutFJK70sFOOq3L8XDz7M/view?usp=sharing)
- [slides](https://github.com/ConsenSys/secureum-diligence-bootcamp/blob/main/day2/lecture2.pdf)


#### Day 3

- [recording](https://drive.google.com/file/d/1zwbp7VC5Y_wz-cWOyNdFnaB5QZ5RYcxF/view?usp=sharing)


#### Day 4

- [recording](https://drive.google.com/file/d/1frI-bvSH1YNBKYcJFC0ndT4u1Hq5zxlL/view?usp=sharing)
- [slides](https://github.com/ConsenSys/secureum-diligence-bootcamp/blob/main/day4/lecture4.pdf)


### Exercises

#### Day 1

- [Exercise 1](https://github.com/ConsenSys/secureum-diligence-bootcamp/tree/main/day1/exercise1)
- [Exercise 2](https://github.com/ConsenSys/secureum-diligence-bootcamp/tree/main/day1/exercise2)
- [Exercise 3](https://github.com/ConsenSys/secureum-diligence-bootcamp/tree/main/day1/exercise3)


#### Day 2

- [Exercise 1](https://github.com/ConsenSys/secureum-diligence-bootcamp/tree/main/day2/exercise1)
- [Exercise 2](https://github.com/ConsenSys/secureum-diligence-bootcamp/tree/main/day2/exercise2)


#### Day 3

- [Exercise](https://github.com/ConsenSys/secureum-diligence-bootcamp/blob/main/day3/exercise.md)


#### Day 4

- [Exercise 1](https://github.com/ConsenSys/secureum-diligence-bootcamp/tree/main/day4/exercise1)
- [Exercise 2](https://github.com/ConsenSys/secureum-diligence-bootcamp/tree/main/day4/exercise2)


### Scribble

- [Scribble documentation](https://docs.scribble.codes)
- [Scribble open-source tool](https://github.com/ConsenSys/Scribble)
- [Scribble VSCode plugin](https://marketplace.visualstudio.com/items?itemName=diligence.vscode-scribble)
- [Scribbling Smart Contracts for fun - and profit!](https://www.youtube.com/watch?v=gGOK8CXdrGs) (presentation at UnChained 2022)
- [Scribble workshop at Unchained 2021](https://www.youtube.com/watch?v=zWgb5OqBQxY)


### Diligence Fuzzing (DF)

- [DF docs](https://fuzzing-docs.diligence.tools)
- [DF command-line tool](https://github.com/ConsenSys/diligence-fuzzing)
- [Increasing Code Coverage Using Fuzzing Lessons](https://consensys.net/diligence/blog/2022/10/increasing-code-coverage-using-fuzzing-lessons) (blog post)


#### Harvey Fuzzer (optional)

- [Harvey: A Greybox Fuzzer for Smart Contracts](https://mariachris.github.io/Pubs/FSE-2020-Harvey.pdf) (paper published at ESEC/FSE 2020)
- [Short summary video on Harvey](https://www.youtube.com/watch?v=Wv-uIknuhgs)
- [Conference presentation on Harvey](https://www.youtube.com/watch?v=Wv-uIknuhgs)
- [Finding Vulnerabilities in Smart Contracts](https://medium.com/consensys-diligence/finding-vulnerabilities-in-smart-contracts-175c56affe2) (blog post)
- [Fuzzing Smart Contracts Using Input Prediction](https://medium.com/consensys-diligence/fuzzing-smart-contracts-using-input-prediction-29b30ba8055c) (blog post)
- [Fuzzing Smart Contracts Using Multiple Transactions](https://medium.com/consensys-diligence/fuzzing-smart-contracts-using-multiple-transactions-51471e4b3c69) (blog post)
- [Detecting Reentrancy Issues in Smart Contracts Using Fuzzing](https://medium.com/consensys-diligence/detecting-reentrancy-issues-in-smart-contracts-using-fuzzing-e81474ba3a2e) (blog post)
- [Checking Custom Correctness Properties of Smart Contracts Using MythX](https://medium.com/consensys-diligence/checking-custom-correctness-properties-of-smart-contracts-using-mythx-25cbac5d7852) (blog post)
