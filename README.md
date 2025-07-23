# customer-manager

This HTML/CSS provides a clean and responsive user interface for your CRM. It uses Tailwind CSS for utility-first styling and includes basic JavaScript functions to simulate adding, editing, and deleting customers directly in the browser (without backend interaction, as that's the next step).

Next Steps:

Backend Integration: The JavaScript functions (addCustomerToTable, editCustomer, deleteCustomer) currently only manipulate the DOM. In your next stages, you'll replace these with actual API calls to your Spring Boot backend, which will handle the Hibernate queries and database interactions.

Form Validation: You can add more robust client-side form validation using JavaScript.

Dynamic Data Loading: When your backend is ready, you'll fetch the initial customer list from the server and populate the table dynamically on page load.
