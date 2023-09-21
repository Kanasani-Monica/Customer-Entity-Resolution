# Problem Statement
## Customer-Entity-Resolution
Entity/Identity resolution creates a single source of truth for a company's understanding of its customers by linking and consolidating customer data from various sources. Entity resolution is the process of identifying and linking multiple records or data points that refer to the same real-world entity, such as a customer. At its core, it's about ensuring that all the information a company has about a customer is accurate, complete, and up-to-date, regardless of where it resides in their systems. With entity resolution, businesses can create an accurate 360-degree view of their customers, enabling them to make informed decisions, personalize their interactions, and improve customer experiences. This approach helps to eliminate the potential for duplicate, conflicting, or incomplete information, leading to a more cohesive and accurate view of the customer. Sample data attributes used to match & link entities: Name, Address, Date of Birth, etc.

## Build an application UI page and Pre-fill the details:
Create a new account application form with the attributes mentioned in the "Application Form Schema.xlsx" file below. 
Auto-fill the application with Customer's Name, Address, and Date of Birth, from:
The matching Credit Bureau record, if a match is found
The extracted information from the document, if there is no match with Credit Bureau
Provide the ability to edit the information in the application form.
Create an application "Submit" button, and store the information in the backend.

## Creation of Application Form
Create the new account application form. Develop code to populate the new account application form with the matching identity information from Credit Bureau.
Handle potential edge cases or missing information gracefully.
