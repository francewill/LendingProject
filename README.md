# Lending Project 
### Specifications
- The project must be a single user
- User can add clients 
- User can add transactions
- User must have transaction history 
- User have an option to see the transaction history in a specific client
- A transaction can only be deleted once there is no current borrowed money
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
        - Harry current borrowed money = 5000
        - Harry paid 1000 + 250 for interest
        - Harry current borrowed money = 4000
        - Harry paid 1000 + 200 for interest 
        - Harry current borrowed money = 3000
- User can add another transaction even client has an ongoing transaction
