# PayRoll

<todo: application description>

## PayRoll API Routes

### ORDERS
#### GET /orders
Get all orders <br />
https://payrollservice.herokuapp.com/orders <br />

#### GET /orders/{id}
Get specific order <br />
https://payrollservice.herokuapp.com/orders/{id} <br />

#### POST /orders
Create a new order <br />
Params: {description: "description", status: ENUM_STATUS} <br />
ENUM_STATUS: [IN_PROGRESS, COMPLETED, CANCELLED] <br />
https://payrollservice.herokuapp.com/orders <br />

#### DELETE /orders/{id}/cancel
Changes the order status to CANCELED if the order status is IN_PROGRESS <br />
https://payrollservice.herokuapp.com/orders/{id}/cancel <br />

#### PUT /orders/{id}/complete
Changes the order status to COMPLETED if the order status is IN_PROGRESS <br />
https://payrollservice.herokuapp.com/orders/{id}/complete <br />


### Employee

#### GET /employees
Get all employees <br />
https://payrollservice.herokuapp.com/employees <br />

#### POST /employees
Create a new employee <br />
Params: {firstName: "<first_name>", lastName: "<last_name>", role: "<role_description>"} <br />
https://payrollservice.herokuapp.com/employees <br />

#### GET /employees/{id}
Get a specific employee <br />
https://payrollservice.herokuapp.com/employees/{id} <br />

#### PUT /employees/{id}
Update or Create a employee <br />
Params: {firstName: "<first_name>", lastName: "<last_name>", role: "<role_description>"} <br />
https://payrollservice.herokuapp.com/employees/{id} <br />

#### DELETE /employees/{id}
Delete a specific employee <br />
https://payrollservice.herokuapp.com/employees/{id} <br />

[comment]: <> (Mica <3)

