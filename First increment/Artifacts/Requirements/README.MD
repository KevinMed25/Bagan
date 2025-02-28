# Prioritization of requirements

Based on the MoSCow software requirements prioritization technique:

## Must have:

- ### 1.- Login

  Access to the system must be controlled and will be only for permitted users with the email provided under the institution's domain.

  [Use case](./Use%20case%20-%20Login.pdf "Go to the use case")

- ### 2.- Generate an input voucher

  The software must be able to generate an input voucher that allows adding new items
  to the inventory, this voucher must contain the fields of:

  - Store of origin
  - Date of preparation
  - Invoice No.
  - Starting No.
  - Item name
  - Item Quantity
  - Warehouse number
  - Unit type
  - Unit price
  - Total price

  [Use case](./Use%20case%20-%20Generate%20an%20input%20voucher.pdf "Go to the use case")

- ### 3.- Generate an output voucher

  The software must be able to generate an output voucher each time an inventory item needs to be removed from the inventory, this voucher must contain the following fields:

  - Requesting area
  - Date
  - Warehouse Folio
  - Article key
  - Quantity requested
  - Unit type
  - Item description
  - Quantity delivered
  - Unit price
  - Total

  [Use case](./Use%20case%20-%20Generate%20an%20output%20voucher.pdf "Go to the use case")

- ### 4.- Generate a current stock table

  The software must be able to output a current stock table, containing the fields:

  - Item number
  - Item name
  - Article key
  - Unit type
  - Number of stocks

  [Use case](./Use%20case%20-%20Generate%20a%20current%20stock%20table.pdf "Go to the use case")

- ### 5.- Generate a summary of a specific product

  The software must be able to issue a general summary of inputs and outputs of a specific product containing the fields of:

  - Item name
  - Article key
  - Starting No. 
  - Warehouse number
  - Unit type
  - Inputs number for article 
  - Outputs number for the article
  - Number of units in stock
  - Last unit cost per item
  - Average cost per item

  [Use case](./Use%20case%20-%20Generate%20a%20summary%20of%20a%20specific%20product.pdf "Go to the use case")

  - ### 6.- Generate a monthly summary of the stock

  The software must be able to issue a monthly summary of inputs and outputs of all registered products, containing the following fields:

  - Item number
  - Item name
  - Article key
  - Unit type
  - Number of stocks

  [Use case](./Use%20case%20-%20Generate%20a%20monthly%20summary%20of%20the%20stock.pdf "Go to the use case")

## Should have:

- The system must provide error messages that are informative and end-user oriented,
  displaying a pop-up window indicating the error entered and the possible solution.

- The application must be usable in any web browser without the need to install any
  third-party software.

- All formats generated by the program can be saved in PDF format ready for printing.

## Could have:

- The system must have well-formed graphical interfaces.

- The page must be hidden and not indexed by web browsers.

- The learning time of the system by a user should be less than 4 hours.

- The system must be available 99.99% of the time a user attempts to access it.

- When entering the product output key the product description field will load a preselection list with all the products corresponding to that key.

## Will not have:

- The software shall be optimized for use on touch devices.

- The system must have properly structured user manuals.

- The unit of measurement field of the product will consist of a preset list.

- The output voucher folio will be automatically generated based on the last one registered.

- The applicant area field will consist of a pre-selection list (must be previously registered
  in the system).

- The web application must have a "Responsive" design in order to ensure proper viewing
  on multiple personal computers, tablet devices and smartphones.

- The software shall be able to be used on Windows and OSX operating system devices.
