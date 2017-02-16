ArgumentationDynamics
======================

This project's subject is the **dynamics of abstract argumentation systems**.

Given an abstract argumentation system, and assuming that specific sets of attacks could be added to it (or removed from it), we ask the following question:
how to make a specific argument accepted (or rejected), by making a **minimal change** (as far as attack additions and removals are concerned)?

In this work, we propose to encode abstract argumentation systems with the help of the **_Maude language_**, and then 
to use the **_Maude rewriting system_** (http://maude.cs.illinois.edu) in order to find _every possible way_ to:

1. Make a focal argument accepted / rejected.
2. Make minimal structural changes in the initial system. 

The code provided here has been used in our research paper **_Rewriting Rules for the Computation of Goal-Oriented
Changes in an Argumentation System_** (**CLIMA'13**).