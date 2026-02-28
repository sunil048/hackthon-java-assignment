# Questions

Here are 2 questions related to the codebase. There's no right or wrong answer - we want to understand your reasoning.

## Question 1: API Specification Approaches

When it comes to API spec and endpoints handlers, we have an Open API yaml file for the `Warehouse` API from which we generate code, but for the other endpoints - `Product` and `Store` - we just coded everything directly. 

What are your thoughts on the pros and cons of each approach? Which would you choose and why?

**Answer:**
```txt
OpenAPI Spec Approach:
Pros:
- Provides a clear, standardized contract for the API, which can be easily shared and understood by different teams and stakeholders.
- Enables automatic code generation, which can speed up development and reduce boilerplate
cons:
- Human mistake
- Need to handle very carefully while updating

Direct Approach :
Pros:
- Well designed api
- Less human mistakes
Cons:
- Time consuming
- Tightly coupled with code

Conclusion :
 Open Api is more usefull for get call, validations
 Direct approach is usefull for complecated end point which includes request body

```

---

## Question 2: Testing Strategy

Given the need to balance thorough testing with time and resource constraints, how would you prioritize tests for this project? 

Which types of tests (unit, integration, parameterized, etc.) would you focus on, and how would you ensure test coverage remains effective over time?

**Answer:**
```txt

```
