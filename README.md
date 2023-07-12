# Lending Project 
### Specifications
- Single user
- User can add clients 
#### Classes
- The user has the following:
    - Name
    - Email
    - Password
    - Total lended money
    - Current lended money
    - Total income
- The clients has the following:
    - Name
    - Total borrowed money
    - Current borrowed money
- A transaction has the following:
    - Name of client who borrowed money
    - Date of transaction
    - Amount of the borrowed money
    - Status of transaction (paid/ ongoing)
    - Current value of borrowed money
#### Transaction process
- Once the user add a client, user must add its first transactions already
- Every lended money have 5% interest 
- Every transaction has a due date (monthly) where the client must pay its borrowed money.
- A client can pay any amount for their borrowed money but every transaction there is 5% (current borrowed money) interest.
    - Example 
        - France current borrowed money = 5000
        - France paid 1000 + 250 for interest
        - France current borrowed money = 4000
        - France paid 1000 + 200 for interest 
        - France current borrowed money = 3000
- User can add another transaction even client has an ongoing transaction