# Capstone Team: Murco

The Murphy Wall Shipping Application is a software development project designed to support Murphy Wall's shipping operations. The team is developing the application in Zoho Creator to provide a centralized interface for accessing product information, invoices, and shipment-related functionality.
The goal is to develop a user-friendly, reliable application that supports Murphy Wall's Shipping workflow while meeting the project's functional and technical requirements. 

# Tech Stack
- Zoho Creator
- Deluge


# Project Structure
```text
Murphy-wall-shipping/
│
├── README.md
└── src/
    ├── Home/           # Startup of application, all sub-tabs located here
    ├── Products/       # Product information and log
    ├── Invoices/       # All invoices and create invoice option
    ├── Shipments/      # All shipments and create shipments
```
# Application Flow
The application opens to the Main menu startup screen and lets the user select options from Home, Products, Shipments, and Invoices.
- Home: Users access the application's main navigation and available sections.
- Products: Users access product information, including relevant product details and UPC numbers.
- Invoices: Users access invoice-related information associated with shipping operations.
- Create Shipments: Users enter the information required to create a shipment.
- All Shipments: Users access the shipment listing to review available shipment records.

# Completed Features
- Initial application interface designs created in Figma.
- Core application sections identified: Home, Products, Invoices, and Shipments.
- Create Shipment form with input fields.

# Current Limitations
- Product, invoice, and shipment data must be validated for accuracy and consistency.
- Required-field validation and error handling need to be verified.
- Cross-platform compatibility and usability require testing.
- The Shipments "Total Shipments, In Transit, and Delivered" tiles are demonstration placeholders. Selecting one does not yet launch a real application option.

# Work Currently in Progress
- Adding a signature option in the shipping form area.
- Adding a searchable list of products, codes, numbers, and pictures into Zoho.
- Ensuring the Invoices tab creates and stores invoices correctly.
- Making the interface user-friendly.

# Future Work

The following tasks are available for future development. Team members should communicate which task they are taking before beginning work to avoid duplicate changes

### User Interface
- Making the interface user-friendly.
- Improve visual consistency across the start screen, Products, Invoices, and shipments windows.
- Connect the dashboard tiles to real actions (open applications, files, or messages).
- Review the interface across supported screen sizes and devices.
### Product Management
- Improve the organization and display of product information.
- Implement or refine product search and filtering, if required.
- Validate product data to reduce incomplete or incorrect entries.
### Invoice Management
- Refine and display the organization of invoice information.
- Verify that invoice records contain required information.
- Review relationships between invoices, products, and shipment records where applicable.
- Improve invoice data validation and handling of missing information.
### Shipment Management
- Complete and refine the Create Shipment Workflow.
- Improve the All Shipments page for reviewing shipment records.
- Validate required shipment information before records are saved.
- Verify that shipment details are saved and displayed correctly.
### Automation and Notifications
- Implement shipping confirmation emails.
- Verify that automated workflows run under the correct conditions.
- Test notifications to ensure that the appropriate information is delivered to intended recipients.
# Known Issues
- Incorrect or incomplete product, invoice, or shipment data.
- Unexpected behavior during Invoice creation.
- Navigation or usability issues across application pages.
- Confirmation emails are not yet fully implemented or tested.

# Team Notes
- Future tasks should be selected from this README and announced to the team before implementation.
- Team members should keep the repository updated with relevant code.
