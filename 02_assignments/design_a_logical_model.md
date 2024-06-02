# Assignment 1: Design a Logical Model

## Question 1
Create a logical model for a small bookstore. 📚

At the minimum it should have employee, order, sales, customer, and book entities (tables). Determine sensible column and table design based on what you know about these concepts. Keep it simple, but work out sensible relationships to keep tables reasonably sized. Include a date table. There are several tools online you can use, I'd recommend [_Draw.io_](https://www.drawio.com/) or [_LucidChart_](https://www.lucidchart.com/pages/).

![image](https://github.com/NabZaf/sql/assets/67026567/d7bf371f-cf00-43a3-aac6-0c2771f4ee46)


## Question 2
We want to create employee shifts, splitting up the day into morning and evening. Add this to the ERD.


![image](https://github.com/NabZaf/sql/assets/67026567/b2287116-a3e3-41bd-86b9-b9b219c6c493)


## Question 3
The store wants to keep customer addresses. Propose two architectures for the CUSTOMER_ADDRESS table, one that will retain changes, and another that will overwrite. Which is type 1, which is type 2?

_Hint, search type 1 vs type 2 slowly changing dimensions._

Bonus: Are there privacy implications to this, why or why not?
Saving the address should require customer consent. 

Does not retain changes - Type 1
![image](https://github.com/NabZaf/sql/assets/67026567/9b7d84b6-9196-4c31-9863-7920f4c6f98d)

Retains Changes in address Type2
![image](https://github.com/NabZaf/sql/assets/67026567/5bcd253c-f160-42dc-9d23-69ad7745050d)


```

```

## Question 4
Review the AdventureWorks Schema [here](https://i.stack.imgur.com/LMu4W.gif)

Highlight at least two differences between it and your ERD. Would you change anything in yours?
```
1.	The AdventureWorks Schema has far more tables and far more relationships. Each table is also in greater detail.
2.	The AdvenureWorks schema does not whether the relationships are one-to-one, one-to-many or many-to-many.
If I had more time, I would make my diagram in more detail. I would think about what I need in the tables to better understand customer preferences and to build a better relationship with my customers. Of course, One needs to keep data privacy and other ethical issues in mind.

```



# Criteria

[Assignment Rubric](./assignment_rubric.md)

# Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `June 1, 2024`
* The branch name for your repo should be: `model-design`
* What to submit for this assignment:
    * This markdown (design_a_logical_model.md) should be populated.
    * Two Entity-Relationship Diagrams (preferably in a pdf, jpeg, png format).
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/sql/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `model-design`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-3-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
