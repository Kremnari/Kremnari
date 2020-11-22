### Purpose of this document
This document outlines the fields present in each table of a jds2 file

Note on arrays: Numerical arrays will, for the moment, not be used.  This is to allow referencing to remain absolute


## File structure
### Version
Stores information about the specification used to maintain the jds2 file

### Meta
Contains information relevant to the developers

### Links
Further information about reference links reside here

### Tables
Name
Definition
Content

### Definitions
Name : string
Fields :

### Types
Name
Subtypes
Validator : function
####  Subtypes
Parameters : 

### Functions
Functions are passed to js's Function constructor with a parameter named "value"
The return should be a Boolean to determine whether it is valid
TODO: allow a second argument called "params" that constitutes extra qualifies to the field
$Name
$Content
