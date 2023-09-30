# Company-information-database#
PROJECT DESCRIPTION:

This project involves the creation and management of a relational database called "Company_information." The database is designed to store and organize information related to employees, branches, clients, sales transactions, and suppliers for a fictional company. The primary purpose of this project is to effectively manage, and query data related to the company's organizational structure, sales, and relationships with clients and suppliers.


About the Data:

The database comprises several tables:
1.	employee: Stores information about employees, including their ID, name, birth date, gender, salary, supervisor ID, and branch assignment.
2.	branch: Contains data on company branches, including branch ID, branch name, manager ID, and manager’s start date.
3.	client: Holds data about clients, including client ID, client name, and the branch they are associated with.
4.	works_with: Records sales transactions between employees and clients, including employee ID, client ID, and total sales.
5.	branch_supplier: Stores information about suppliers serving different branches, including branch ID, supplier name, and supply type.


BUSINESS QUESTIONS ANSWERED:

1.	Employee and Branch Information: The database allows for the retrieval of employee information, such as their names, branches, and supervisors. This information can be used to assess the company's organizational structure.
2.	Sales Transactions: The "works_with" table enables tracking of sales transactions between employees and clients. This data can answer questions related to revenue generation, top-performing salespeople, and client relationships.
3.	Supplier Relationships: The "branch_supplier" table provides insights into the company's supplier relationships and the type of supplies each branch receives.
4.	Client Information: The "client" table contains data about the company's clients and their associations with specific branches. This information can be used to analyze client distribution and branch-client relationships.


APPROACH:

The project follows these key steps:
1.	Database Creation: The "Company_information" database is created to organize and store relevant data.
2.	Table Creation: Several tables are defined to capture different aspects of the company's operations, including employees, branches, clients, sales transactions, and suppliers.
3.	Data Population: Data is inserted into the tables to simulate a company's organizational structure, sales, and supplier-client relationships.
4.	Querying and Analysis: SQL queries are used to extract valuable insights from the data, including employee details, sales figures, and client relationships.
5.	Triggers: Triggers are implemented to automatically capture specific events, such as the addition of new employees, and store relevant information in the "trigger_test" table.


RESULTS:

The project successfully created a relational database that provides valuable insights into the company's operations. Users can query the data to answer business-critical questions, such as identifying top-performing salespeople, analyzing client relationships, and monitoring supplier interactions. Additionally, triggers are implemented to automate event tracking within the database, offering real-time visibility into critical events, such as new employee additions.
Overall, this project showcases the power of a well-structured relational database in organizing and analyzing data to support informed business decisions and streamline company operations. It provides a foundation for further data analysis and reporting to enhance the company's performance and efficiency.



CONCLUSION;


In conclusion, the creation and management of the "Company information" relational database project serve as a valuable tool for organizing, storing, and analyzing data related to the company's employees, branches, clients, sales transactions, and suppliers. This project achieves its intended purpose of providing insights into various aspects of the company's operations and answering important business questions.
The key takeaways from this project include:
1.	Effective Data Management: The project demonstrates the importance of a well-structured relational database in efficiently managing and storing data. It ensures data integrity and allows for easy retrieval of information.
2.	Business Insights: The database facilitates data-driven decision-making by providing answers to critical business questions. Users can extract information about employee hierarchies, sales performance, client relationships, and supplier interactions.
3.	Automation with Triggers: The inclusion of triggers enhances the database's functionality by automatically capturing and storing relevant events. This automation simplifies event tracking and real-time monitoring.
4.	Data Quality: Proper data management practices ensure data accuracy, consistency, and reliability. This is crucial for making informed decisions and maintaining the company's reputation.
5.	Scalability: The project can serve as a foundation for further expansion and data analysis. As the company grows, additional data can be seamlessly integrated into the database.
In summary, this project illustrates how a well-designed relational database can contribute to better decision-making, operational efficiency, and data organization within a company. It provides a valuable framework for ongoing data analysis and reporting, ultimately helping the company achieve its goals and objectives.


 





