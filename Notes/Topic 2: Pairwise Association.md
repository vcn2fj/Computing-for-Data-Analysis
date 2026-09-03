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

* Issue is that in mining problem we are actually trying to find these rules
  - Enumerate through unique loops, check for symmetry a=b or b=a are the same
  - Counting pairs but also need counts for each item

<img width="542" height="271" alt="image" src="https://github.com/user-attachments/assets/5817512e-c475-4661-a3f7-57f9e51d1979" />

<img width="293" height="204" alt="image" src="https://github.com/user-attachments/assets/13728ae3-166d-4cc3-86f7-00ac9cdbfe06" />

* Assessing efficiency: might do too much work/take too much storage

* General way to think ab algorithm design rules
  - Algorithm that scales linearly is work-optimal

<img width="340" height="283" alt="image" src="https://github.com/user-attachments/assets/acb49a0b-9733-4e31-b019-8f9131b0ee60" />
