# Challenge

Create a simple consumer loan app. The app is a headless web service that exposes the following endpoints:

- Apply for a loan and provide `loan amount`, `term`, `name`, and `personal id`
- List all loans by a borrower (you can skip AuthN and AuthZ)

Lending rules:
- Monthly interest rate: 5%
  
Reject the loan application if:
- Borrower is blacklisted (store blacklisted personal ids in a config file or a database)
- Too many applications from one country in the last 24 hours

Use a 3rd-party service to resolve a country, and store it in a database, together with a loan application. 

### Technical requirements

- Use Java programming language
- Use any JVM language for tests
- You have total control over frameworks, tools, and libraries

### What gets evaluated
- Conformance to business requirements
- Code quality (we value good OO design guided by tests)
- Checkout-and-run convenience

### Happy coding! 👨‍💻
