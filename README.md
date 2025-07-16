# Challenge

Create a simple consumer lending app. The app is a headless web service with the following API:

- Apply for a loan and provide `loan amount`, `term`, `name`, and `personal id`
- List all loans by a borrower (you can skip AuthN and AuthZ)

Lending rules:
- Monthly interest rate: 5%
  
Reject loan application if:
- Borrower is blacklisted (store blacklisted `personal ids` in a config file or a database)
- Application limit exceeded for one country in the last 24h.

Resolve country via any third-party service and persist it alongside the loan application.

### Technical requirements

- Use Java programming language ☕️
- Use any JVM language for tests
- You have total control over frameworks, tools, and libraries

### What gets evaluated
- Conformance to business requirements
- Code quality (we value good OO design guided by tests)
- Checkout-and-run convenience

Summarize critical design decisions in README.md.

### Happy coding! 👨‍💻👩‍💻
