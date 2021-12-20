# Challenge

Create a simple consumer loan app. The app is a headless web service that exposes the following endpoints:

- apply for a loan and provide `loan amount`, `term`, `name`, `surname`, and `personal id`
- list all approved loans
- list all approved loans by a borrower (you can skip AuthN and AuthZ)
  
Do not grant a loan if:
- the application comes from a person whose personal id is blacklisted (store a list of blacklisted ids in a config file or DB)
- too many applications come from a certain country in the last `N` days

Use some external service to resolve a country code and store it in a database, together with the loan application. 

### Technical requirements

Use Java programming language; For tests, use any JVM language. You have total control over frameworks, tools, and libraries.

### What gets evaluated
- Conformance to business requirements
- Code quality (we value good OO design guided by tests)
- Checkout-and-run convenience

### Happy coding! 👨‍💻
