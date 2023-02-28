## exercise 1 
p : "You get A for the exam "
q : "You slove all the exercises in this book"
a/ You get A for the exam but you did not solve all the exercises in this book 
- p $\land$ $\lnot$(q)
b/ if you slove all the exercise in this book , then you will get A fo the exam 
- q $\rightarrow$ p 
## exercise 2 
a/ If you solve all the exercises in this book, then you will get A for the exam. 
p: "you slove all the exercises in this book"
q : "then you will get A for the exam"

contrapositive : you will not get A for the exam , if you don't slove all the exercise in this book 
converse : you will get A for the exam , if you slove all the exercise in this book 
b/ If you do not go to school today, you will be banned from the exam.
p : "you do not go to school today " 
q : "you will be banned from the exam"
contrapositive : you won't be banned from the exam if you go to school today 
conserve : you will be banned from the exam , if you dont go to school today 


c /  I will go to the beach in any hot day 
p : "I will go to the beach "
q : "in any hot day"
contrapositive : if not hot day , i won't go to the beach 
conserve : in any hot day i will go to the beach 

## excersice 3 
Rewrite the following statements in natural language using “p if and only if q” form:  
a/ A necessary and sufficient condition for graduation is that you have to study.  
p: " A necessary and sufficient condition for graduation"
q : "you have to study"
you will gradute if and only if you study 
b/ If you go to school, you’ll get your attendance, and if you took your attendance,  you had gone to school.
p :"you go to school"
q: " you’ll get your attendance"

you will get your attendance if and only if you go to school 

excersice 4 : 
a/ Being over 18 is sufficient to become the US president
IF  you are over 18 , yhen you are sufficient  to become the us president 
b/ You need to study all the lessons to pass the Discrete Structures module. 
if you study all the lessons ,then you will pass  the discrete structure module 

## excersice 5 : 
Using truth table to prove that the following statements are tautology:  
a/ (p $\land$ q) → p  
| p     | q     | (p $\land$ q) → p |
| ----- | ----- | ----------------- |
| true  | true  | true              |
| false | true  | false             |
| true  | false | true              |
| false      |false       |  true                 |
b/ ((p → q) $\land$ (q → r)) → (p → r)

To prove that the statements in question 5 are tautology using logical equivalence laws, we will need to show that each statement is equivalent to a statement that is always true.

a/ $(p \land q) \rightarrow p$

Using the law of implication, we can rewrite the statement as $\neg (p \land q) \lor p$. Then, using the law of DeMorgan's, we can rewrite the negation as $(\neg p \lor \neg q) \lor p$. Finally, we can use the associative and commutative properties to rearrange the terms and get $(\neg q \lor \neg p) \lor p$, which is equivalent to $\neg q \lor (\neg p \lor p)$. Since $\neg p \lor p$ is always true (law of excluded middle), we can simplify the statement to $\neg q \lor \text{true}$, which is always true. Therefore, the original statement is a tautology.

b/ $((p \rightarrow q) \land (q \rightarrow r)) \rightarrow (p \rightarrow r)$

We can use the law of contraposition to rewrite the conditional as $(\neg (p \rightarrow r)) \rightarrow \neg ((p \rightarrow q) \land (q \rightarrow r))$. Next, we can use the law of implication to rewrite $\neg (p \rightarrow r)$ as $p \land \neg r$. Then, using the law of DeMorgan's, we can rewrite $\neg ((p \rightarrow q) \land (q \rightarrow r))$ as $(p \rightarrow q) \land \neg(q \rightarrow r)$.

Using the law of contraposition again, we can rewrite $\neg(q \rightarrow r)$ as $q \land \neg r$. Substituting this into our previous expression, we get $(p \rightarrow q) \land (q \land \neg r)$. Using the distributive property, we can rewrite this as $(p \rightarrow q) \land q \land \neg r$.

Using the law of simplification, we can simplify this to $q \land (p \rightarrow q) \land \neg r$. Then, using the law of contraposition, we can rewrite $(p \rightarrow q)$ as $\neg q \rightarrow \neg p$. Substituting this in, we get $q \land (\neg q \rightarrow \neg p) \land \neg r$.

Using the law of contraposition once more, we can rewrite $(\neg q \rightarrow \neg p)$ as $(p \rightarrow q)$. Substituting this in, we get $q \land (p \rightarrow q) \land \neg r$, which is equivalent to $(q \land p) \rightarrow (q \land r)$.

Thus, we have shown that the original statement is equivalent to $(q \land p) \rightarrow (q \land r)$, which is a tautology by the law of syllogism. Therefore, the original statement is also a tautology.