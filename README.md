<p align="center">
  <a href="" rel="noopener">
 <img src="https://i.ibb.co/4fj8Xjf/New-Project-1.png" alt="Project logo"></a>
</p>
<h3 align="center">OzrenBet</h3>

<div align="center">

  [![Hackathon](https://img.shields.io/badge/hackathon-name-orange.svg)](http://hackathon.url.com) 
  [![Status](https://img.shields.io/badge/status-active-success.svg)]() 
  [![GitHub Issues](https://img.shields.io/github/issues/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/issues)
  [![GitHub Pull Requests](https://img.shields.io/github/issues-pr/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/pulls)
  [![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE.md)

</div>

---

<p align="center"> OzrenBet is a Sports Betting website which was made for a School Project for my Programming Class. 
    <br> 
</p>

## 📝 Table of Contents
- [Problem Statement](#problem_statement)
- [Idea / Solution](#idea)
- [Dependencies / Limitations](#limitations)
- [Future Scope](#future_scope)
- [Setting up a local environment](#getting_started)
- [Usage](#usage)
- [Technology Stack](#tech_stack)
- [Contributing](../CONTRIBUTING.md)
- [Authors](#authors)
- [Acknowledgments](#acknowledgments)

## 🧐 Problem Statement <a name = "problem_statement"></a>
OzrenBet is a Sports Betting website, made for a School Project. Sports Betting is huge in Bosnia and Herzegovina, being one of the largest industries. 
This Project was never meant to be fully functional, due to certain limitations (i.e Payment Systems and getting actual Offers from Betters) but it is made to show what a High School Junior student could make within a timeline of 3 weeks.

For now the Project is planned to have: 
1. Basic Betting System
2. Basic Payment/Withdrawal System - using my own "payment" system, basically just FireStore collection with generated payment Tokens, similar to xBet. 
3. Basic Interface :)

## 💡 Idea / Solution <a name = "idea"></a>
The solution for the given problem is to use Firebase/Firestore combination for the back end, with React.JS on the front end. Firebase provides us the opporutunity to use pre-defined functions to access the Authentification System, noSQL Database and a File Manager. Besides that, Firebase is asynchrous, proving us with a chance to use real-time modifications.
This section is used to describe potential solutions. 

Once the ideal, reality, and consequences sections have been 
completed, and understood, it becomes easier to provide a solution for solving the problem.

## ⛓️ Dependencies / Limitations <a name = "limitations"></a>
- What are the dependencies of your project?

  This project is dependant on Firebase/Firestore and React
- Describe each limitation in detailed but concise terms

  The main limitation is the payment system. Due to this being a school project, I did not implement any payment systems (ie. Stripe) but have instead used a custom-built payment system similar to xBet (12 character alphanumeric code coresponding to a certain cash ammount)
- Explain why each limitation exists

  That limitation exists because I don't really have enough cash to test it out, and I wasn't bothered to use stripe test
- Provide the reasons why each limitation could not be overcome using the method(s) chosen to acquire.
- Assess the impact of each limitation in relation to the overall findings and conclusions of your project, and if 
appropriate, describe how these limitations could point to the need for further research.

## 🚀 Future Scope <a name = "future_scope"></a>
Write about what you could not develop during the course of the Hackathon; and about what your project can achieve 
in the future.

## 🏁 Getting Started <a name = "getting_started"></a>
These instructions will get you a copy of the project up and running on your local machine for development 
and testing purposes. See [deployment](#deployment) for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them.

```
Give examples
```

### Installing

A step by step series of examples that tell you how to get a development env running.

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

## 🎈 Usage <a name="usage"></a>
Add notes about how to use the system.

## ⛏️ Built With <a name = "tech_stack"></a>
- [MongoDB](https://www.mongodb.com/) - Database
- [Express](https://expressjs.com/) - Server Framework
- [VueJs](https://vuejs.org/) - Web Framework
- [NodeJs](https://nodejs.org/en/) - Server Environment

## ✍️ Authors <a name = "authors"></a>
- [@kylelobo](https://github.com/kylelobo) - Idea & Initial work

See also the list of [contributors](https://github.com/kylelobo/The-Documentation-Compendium/contributors) 
who participated in this project.

## 🎉 Acknowledgments <a name = "acknowledgments"></a>
- Hat tip to anyone whose code was used
- Inspiration
- References
