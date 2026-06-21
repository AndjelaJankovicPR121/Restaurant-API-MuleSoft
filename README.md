\# Restaurant API



REST API developed using MuleSoft and MySQL.



\## Features



\- Customer CRUD

\- Order CRUD

\- Employee CRUD

\- Restaurant Table CRUD

\- Payment CRUD



\## Additional functionality



\### Customer filtering



GET /customers supports optional active header:



active=true

active=false



\### Customer upsert



PUT /customers/{id}



If customer does not exist, a new customer is automatically inserted.



\### ERP integrations



Large orders (amount > 100):



\- written to internalERP XML

\- written to chineseERP JSON



\### Technologies



\- MuleSoft

\- RAML

\- MySQL

\- DataWeave 2.0

