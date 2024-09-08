# booking-calendar-server-backend

docker compose up -d --build

# /src/internal/modules
## **MODULES:**
- constant: define enum, variable common
- controller: receive request
- dto: data object transfer from controller -> service -> repository
- filters: filter input for model query
- mappers: mapping data model to object response
- entities: define entity mapping document NoSQL
- models: define modeling mapping table RDS (MySQL)
- repositories: define repository layer, it is operation with model
- request: data send from client to server
- response: data send from server to client

