# Business rules

## Account management
A user must be logged in to use the sofware
A user must input a valid email to create an account
User email must not be already used
A user must input a valid password to create an account
Account must be verified by mail confirmation
User cant request a password reset link
## Profile management
A user has a first name (required)
A user has a last name (required)
A user has a email address (required)
A user has a phone number (not required)
A user has a postal adress (not required)
A user with an associated business is a business owner
A user can upload his signature
## Postal adress management
Postal address has a street number
Postal address has a street name
Postal address has a ZIP code
Postal address has a city
Postal address may has optional field
## Business management
A business is created by a user
A business is owned by a user
A business has a SIRET
A business has an APE code
A business has a tax code
A business can has a logo
Businesses are only visible by their owner 
## Performance management
A performance can be a service provided or a good sold
A performance is related to a company
A performance has a price
A performance can be created, edited or deleted by a business owner
A performance is associated with a tax
## Estimate management
An estimate can be created, edited or deleted by a business owner
An estimate has at leat one perfomance associated
An estimate can has the same performance associated multiple times
An estimate has a customer
An estimate has a creation date
An estimate may has a discount
An estimate has a state (emitted or accepted)
An estimate has an expiration date
An estimate has an expected delivery time
## Customer management
A user can create, update or edit a customer
A customer can be a professionnal or individual
A professionnal customer has a business name (required)
An individual customer has a first name (required)
An individual customer has a last name (required)
A customer has a mail (optional)
A customer has a phone number (optional)
A customer has a postal address (optional)
## Invoice management
A business owner can create, update or edit an invoice
An invoice requires an approuved estimate
An invoice has two states (emitted or paid)
An invoice has a price surcharge (set by default to zero)
An invoice has a payment limit date
An invoice has a payment date
An invoice has a creation date
## Expense management
A business owner can create, update or edit an expense
An expense has a title
An expense has a price
An expense has a date