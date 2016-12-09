# Intermediate Ruby methods - approx 4-5 hours

**Goal:**

To demonstrate understanding of ruby methods.

**Assignment:**

Choose one of the following exercises and create a method that creates the behavior indicated.

**Exercise A: Rotate**

Create a method that rotates the items in an array by n steps and returns the rotated array. The method should accept an array and how many spaces it should rotate (n).
  
**Do not use Ruby's built-in `Array.rotate` method.**

If your input is: `["cat", "dog", "mouse", "shoe"], 2`
Your output should be: `["mouse", "shoe", "cat", "dog"]`

If your input is: `[1, 2, 3, 4, 5], 1`
Your output should be: `[2, 3, 4, 5, 1]`

**Challenge:**

Create the method in such a way that it can accept negative values able to accept negative `n` values and rotate your array backwards.

If your input is: `["cat", "dog", "mouse", "shoe"], -1`
Your output should be: `["dog", "mouse", "shoe", "cat"]`

**Exercise B: Factorial**

Create a factorial method. A factorial is the evaluation of `n!` - This number is calculated by multiplying every number from 1 to and including n.

The first few factorials are:

1!   = 1   = 1
2!   = 2   = 1 * 2 
3!   = 6   = 1 * 2 * 3 
4!   = 24  = 1 * 2 * 3 * 4 
5!   = 120   = 1 * 2 * 3 * 4 * 5
6!   = 720   = 1 * 2 * 3 * 4 * 5 * 6

We use factorials for various different uses in mathematics. A common real-life use case would be if you wanted to figure out how many different ways a certain set of items could be arranged in a series. (This would be known as a permutation)

Say we had four pictures, and we wanted to figure out how many ways we could arrange the four pictures next to each other. We could use 4 factorial. Giving us 24 possible configurations of the four paintings.

**Do not use Ruby's built-in `Math.factorial` method.**

If your input is: `6`
Your output should be: `720` (1 * 2 * 3 * 4 * 5 * 6)

If your input is: `7`
Your output should be: `5040` (1 * 2 * 3 * 4 * 5 * 6 * 7)

**Challenge:**
If your input is a negative integer
Your output should be: `"undefined"`

If your input is: `0`
Your output should be: `1`

**Note:** You are urged to attempt both problems, however only one should be submitted for grading. You can choose which assignment you would like to submit.

**Grading Criteria:**

- The chosen solution should explicitly fulfill the requirements noted in each exercise
- The chosen solution should have a comment indicating which it's solving
- Ruby code runs with no errors
- **Note:** Challenges are optional but encouraged

**Complete =** Meets above grading criteria.

**Incomplete =** Does not meet grading criteria. Needs improvement or missing submission. 