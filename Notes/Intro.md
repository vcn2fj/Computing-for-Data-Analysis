### Topic 0: Course Overview

* goal: understand how to build a basic data analytics pipeline
(raw data -> preprocessing/clean/transform -> analysis through models -> outputs/visualization/postprocessing)
* Computational concerns:
1. Is there an algorithm to compute f(x), exactly or approx.?
2. Given a program to compute f(x), is it correct?
3. Given a correct program, is it efficient?

### Topic 2: Pairwise Association

* Problem: Imagine you are an online retailer w/ data such as all your customer's receipts. How can you cross markdown or recommend items?
  
<img width="542" height="303" alt="image" src="https://github.com/user-attachments/assets/cd3f0b45-f615-4f6f-8093-349032e3cb86" />

* Given a set of receipts, and each receipt, ri, is itself a set of items or an itemset. Assume an item appears at most once on an itemset (limit one per customer). Find all instances a rule such as a customer that buys rice (a) also buys beans (b)

<img width="524" height="265" alt="image" src="https://github.com/user-attachments/assets/964e075c-2eda-4173-8eee-742bdf87cc84" />

<img width="536" height="208" alt="image" src="https://github.com/user-attachments/assets/09700728-ae68-4ed8-821e-1368bca93c10" />

<img width="541" height="300" alt="image" src="https://github.com/user-attachments/assets/e3ecb7db-21f8-4ca2-8c5e-e1f5a7500c5f" />

<img width="530" height="302" alt="image" src="https://github.com/user-attachments/assets/9e894b94-4ce2-4aca-aece-53e83fe6e43b" />

<img width="535" height="283" alt="image" src="https://github.com/user-attachments/assets/c6fcf082-2a68-4cb8-9e4a-bb0695c651a9" />

* Support is the joint prob of  x and y and confidence is the conditional probability of y given x
