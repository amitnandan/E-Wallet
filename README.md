# E-Wallet

### Design:
    There is one Parent Application Containing Various Microservices with their respective database.

    To have conversation between each microservice used Kafka.

### API'S
    user -> POST
    user -> GET
    admin/../user -> GET
    user/{userId} -> GET
    txn -> POST

### Features:
    ->transaction between user's
    ->account updation
    ->transaction history
    ->transaction notification
    ->Event driven updation
