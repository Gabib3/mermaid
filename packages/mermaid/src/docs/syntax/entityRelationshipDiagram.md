```mermaid
erDiagram
  Entity01 | Person |
  Entity02 | Address |
  Entity01 ||--o{ RelationshipID : has
  Entity02 ||--o{ RelationshipID : belongs to
  Entity01 | PersonID : PK
  Entity01 | FirstName : String
  Entity01 | LastName : String
  Entity01 | DateOfBirth : Date
  Entity02 | AddressID : PK
  Entity02 | Street : String
  Entity02 | City : String
  Entity02 | State : String
  Entity02 | PostalCode : String
