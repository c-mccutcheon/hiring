# Vanquis Coding Exercise
-- **What this is for**

This is a deceptively intricate, small exercise, which will expose a good amount about most programmers. It covers analytical thinking, problem solving, knowledge of types and operators, performance via short-circuiting and loop optimization.

Ask for unit tests to further find out about how a candidate may structure code in a life-like situation.

-- **The exercise**

Create a Visual Studio (2015/1017) solution to the following problem:

"Write a function to multiply two integer values A and B, without using the arithmetic operators (* or /)."

Code should be production ready, with supporting tests as deemed required.

Please send your submission in an archive file (zip or rar) to : [emailaddress_here]

-- **What to look for**

- Well named method
- Correct types used for input
- Short-circuiting the method if input A or B is equal to 0
- Using Absoute value of A and B for the calculation loop
- Loop optimization (use lower-bound of A or B to loop by)
- Long/Int64 as a calculated value type, to avoid arithmetic overflows of Int32 types
- Negating the return value via operator if ONE of A or B was negative (negative + positive = negative, negative + negative = positive, positive + positive = positive)

A few good solid unit tests proving their function. Look for example tests covering:

- Value A or B is 0
- Value A or B is negative
- Large numbers for value A or B
