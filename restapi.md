# API #

## Resource service API ##

### Unit-side related API ###


**Unit operations**

| Method    | Path          | Parameters    | Body      |
|:---------:|:-------------:|:-------------:| :--------:|
| GET       | /u/units/     |               |           |
| GET       | /u/units/     | {unitId}      |           |
| POST      | /u/units/     |               | {Unit}    |
| PUT       | /u/units/     | {unitId}      | {Unit}    |
| DELETE    | /u/units/     | {unitId}      |           |

**Consultant operations**

| Method    | Path              | Parameters        | Body          |
|:---------:|:-----------------:|:-----------------:| :------------:|
| GET       | /u/consultants/   |                   |               |
| GET       | /u/consultants/   | {consultantId}    |               |
| POST      | /u/consultants/   |                   | {Consultant}  |
| PUT       | /u/consultants/   | {consultantId}    | {Consultant}  |
| DELETE    | /u/consultants/   | {consultantId}    |               |

**Contract operations**

| Method    | Path              | Parameters    | Body          |
|:---------:|:-----------------:|:-------------:| :------------:|
| GET       | /u/contracts/     |               |               |
| GET       | /u/contracts/     | {contractId}  |               |
| POST      | /u/contracts/     |               | {Contract}    |
| PUT       | /u/contracts/     | {contractId}  | {Contract}    |
| DELETE    | /u/contracts/     | {contractId}  |               |

### Customer-side related API ###

**Customer operations**

| Method    | Path              | Parameters    | Body          |
|:---------:|:-----------------:|:-------------:| :------------:|
| GET       | /u/customers/     |               |               |
| GET       | /u/customers/     | {customerId}  |               |
| POST      | /u/customers/     |               | {Customer}    |
| PUT       | /u/customers/     | {customerId}  | {Customer}    |
| DELETE    | /u/customers/     | {customerId}  |               |

**Consultant operations**

| Method    | Path              | Parameters        | Body          |
|:---------:|:-----------------:|:-----------------:| :------------:|
| GET       | /u/consultants/   |                   |               |
| GET       | /u/consultants/   | {consultantId}    |               |
| POST      | /u/consultants/   |                   | {Consultant}  |
| PUT       | /u/consultants/   | {consultantId}    | {Consultant}  |
| DELETE    | /u/consultants/   | {consultantId}    |               |

**Assignment operations**

| Method    | Path                | Parameters      | Body          |
|:---------:|:-------------------:|:---------------:| :------------:|
| GET       | /u/assignments/     |                 |               |
| GET       | /u/assignments/     | {assignmentId}  |               |
| POST      | /u/assignments/     |                 | {Assignment}  |
| PUT       | /u/assignments/     | {assignmentId}  | {Assignment}  |
| DELETE    | /u/assignments/     | {assignmentId}  |               |
