# Cable Company APP


## Instructions For What Is Needed:
You will build an internet/cable company’s customer tracking system. Your customer (the internet
company) requires the following from your application: <br>
  • You must store the following information:<br>
  o Customer information, this must include the customer's name, number, and the
  locations where they have services from the company. Note, a customer can own
  multiple locations.<br>
  o Address of locations (1234 Street Rd. City, State)<br>
  o Equipment at locations (router, modem, etc.).<br>
  o Services at locations (internet, cable, etc.)<br>
  o Cost of services and equipment. These are flat rates per service/equipment that can be
  used to create customer bills.<br>
  o Billing information, including amount due each month, credit card on file, when the last
  payment was made, and if they are late on payment (You can assume they bill each
  month, so it can simply be the month (August) rather than the date (Jan 01 2023). If you
  want to store dates, that is fine too.)<br>
  • The user must be able to:<br>
  o Insert new customers<br>
  o Remove customers <br>
  o Search for customers by name or location, retrieve the last payment date for customer. <br>
  o View all customers who are late on payment <br>
  o Update last payment made <br>
  o Add and remove services and equipment for a customer <br>
  o Change cost of service/equipment <br>
  o Change bill amount due each month for a customer (or you can automatically due this
  when service/equipment costs are changed)<br>
  • Note, a customer can have multiple locations. You can either assume they get billed per location
  or one bill combining the locations. <br>

## Assumptions:
Assumptions:
-The user of the application is an employee, who is allowed to view all data and can get id numbers when needed
-The user must add a billing cycle for each user every month (if a customer ends service, they just stop adding billing)
-Services and equipment can only be added or removed at the start of a new billing cycle
-The user will provide a proper date format (Input issues could be solved with GUI)
-The user is trained on the system and understands the order of adding a new customer(customer information, location information, billing information, equipment/service information).
