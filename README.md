# HR_ANALYSIS
1. Core Project Components
Based on the file headers in your text, the project is structured with these essential Power BI elements:

DataModel: This is the "brain" of your file. It contains the data relationships, calculated columns, and DAX measures.

Report/Layout: This defines the visual layer—where your charts are placed, their colors, and which filters are applied to each page.

Connections: This stores the details of where your data is coming from (e.g., SQL databases, Excel files, or Web APIs).

2. Visual & Theme Customization
Your project includes specific branding and design assets:

Custom Theme: The file Report/StaticResources/SharedResources/BaseThemes/CY26SU02.json indicates you are using a specific color palette and JSON-defined theme for visual consistency.

Background Image: The presence of BG12_(1)6979292295539123.jpg suggests you have a custom-designed background or wallpaper applied to your report pages to give it a professional "UI/UX" feel.

3. Metadata and Security
Metadata: This section tracks the version of Power BI Desktop used to create the file and the lineage of the data.

SecurityBindings: This handles the permissions and potentially Row-Level Security (RLS) settings defined within the model to restrict data access based on the user.

4. Internal Data Schema
The large block of encoded text under DataModel represents the TMSL (Tabular Model Scripting Language). This section manages:

Relationships: How your tables (like "Sales" and "Date") connect to each other.

M-Query: The "Power Query" steps used to clean and transform the data before it loads into the visuals.
