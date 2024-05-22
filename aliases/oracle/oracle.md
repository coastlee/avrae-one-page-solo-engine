**The Oracle**

This oracle is crafted from the free [One Page Solo Engine](https://preview.drivethrurpg.com/en/product/337254/one-page-solo-engine) toolkit. Check it out!
_ _

**The Oracle (Yes/No)**
When you need to ask a simple question, choose the likelihood and roll 2d6.

*Example.* `!oracle Do I have a question? likely`
_ _

**The Question**
--------------
To ask the Oracle a question, you must supply a question that ends with a question mark (**?**). Otherwise, the oracle will tell you to ask a question.

- *Example 1.* `!oracle is there a river nearby?`
- *Example 2.* `!oracle is there a river nearby? likely`
- *Example 3.* `!oracle is there a river nearby? unlikely -v`
_ _

**Likelihood**
-----------
> *Required?* No
> *Default Value.* `even`
> *Valid Options.* `even, unlikely, likely`
_ _

Likelihood must be supplied *after* the question. 

- *Example.* `!oracle is there a river nearby? likely`
Likelihood defaults to `even` if you do not supply a value or you supply a value not in the list of **valid options**. You'll get warning lights if you do not supply a **valid option**.

_ _
**Verbose**
---------
> *Required?* No
> *Default Value.* None
> *Valid Options.* Add `-v` after the question mark OR after the likelihood.
_ _

Use this if you want to see a bigger output that includes the table for reference and the generated dice rolls!

- *Good Example.* `!oracle is there a river nearby? likely -v`
- *Good Example.* `!oracle is there a river nearby? -v`
- *Bad Example.* `!oracle is there a river nearby? -v likely`