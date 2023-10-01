## Abstraction

**Summary**

**Subject(s):** What is abstraction?

**Objective:** To understand the concept of abstraction in computer science, its significance, and its various applications and manifestations in software development and problem-solving.

**Explanation:**

Abstraction in computer science refers to the process of simplifying complex systems or concepts by focusing on the essential aspects while ignoring unnecessary details. It is a fundamental concept that helps in managing the complexity of software and hardware systems, making them more understandable and maintainable. Abstraction is used throughout computer science and software development to improve design, analysis, and problem-solving.

Here are some key aspects of abstraction in computer science:

* **Hiding Complexity:** Abstraction allows you to hide the intricate and low-level details of a system or component. This makes it easier to work with and understand, as you can interact with a simplified interface or representation.
* **Levels of Abstraction:** Abstraction can occur at multiple levels in a computer system. For example, you can abstract hardware details when programming in a high-level language like Python, and you can abstract implementation details when designing software modules.
* **Data Abstraction:** Data abstraction involves defining data types and structures that encapsulate the data and provide a clear and controlled interface for accessing and manipulating it. Object-oriented programming languages, like Java and C++, heavily rely on data abstraction through classes and objects.
* **Procedural Abstraction:** Procedural abstraction involves encapsulating a sequence of operations or a set of instructions into a single function or method. This simplifies code by allowing you to call a function with a high-level understanding of what it does without needing to know its implementation details.
* **Hierarchical Abstraction:** Hierarchical abstraction organizes complex systems into layers or levels of abstraction. Each layer provides a specific set of services or functions, and the layers interact with each other in a well-defined manner. The OSI model for networking is an example of hierarchical abstraction.

**Abstraction in Software Design:**

During the software design process, abstraction helps in creating clear and modular software architectures. It allows you to define interfaces and specifications for software components without specifying their internal workings, enabling collaboration among teams working on different parts of a project.

**Abstraction and Problem Solving:**

Abstraction is essential in problem-solving because it allows you to break down complex problems into smaller, more manageable parts. You can focus on solving each part independently, which often leads to more efficient and effective solutions.

**Abstraction and Reusability:**

Abstraction promotes code reuse by encapsulating functionality into reusable components or modules. This saves time and effort in software development and maintenance.

**In summary, abstraction is a powerful concept in computer science that simplifies complex systems, improves code organization, and enhances problem-solving. It enables programmers and engineers to work with high-level concepts and interfaces while hiding the underlying complexities, making it an essential tool in designing, implementing, and maintaining software and hardware systems.**

## Three Schema Architecture

The three-schema architecture in DBMS (database management system) is a logical framework that separates the logical and physical aspects of a database into three distinct levels: external, conceptual, and internal. This separation provides a number of benefits, including data independence, modular development, enhanced security, improved performance, data consistency, and support for database evolution.

**External Schema / View Level**

The external schema (also known as view schema) is the highest level of the three-schema architecture. It defines how individual users or groups of users see the data in the database. The external schema is tailored to the specific needs of each user or group of users, and it may hide or aggregate data from the conceptual schema.

**Conceptual Schema**

The conceptual schema (also known as global schema) describes the overall structure of the database from a logical perspective. It defines the entities, attributes, and relationships between entities in the database. The conceptual schema is independent of any specific physical implementation, and it can be used to create multiple external schemas for different users or groups of users.

**Internal Schema / Physical Level**

The internal schema (also known as physical schema) describes the physical storage structure of the database. It defines the data structures, file organizations, and access methods used to store and retrieve data. The internal schema is dependent on the specific DBMS being used, and it is transparent to users and application developers.

**Benefits of the Three-Schema Architecture**

The three-schema architecture provides a number of benefits, including:

* **Data independence:** The three-schema architecture separates the logical view of the data from its physical storage structure. This means that changes to the internal schema can be made without affecting the external schemas or the application programs that access them.
* **Modular development:** The three-schema architecture allows different aspects of the database to be developed independently. For example, the conceptual schema can be developed in parallel with the application programs, and the internal schema can be developed later once the hardware and DBMS have been chosen.
* **Enhanced security:** The three-schema architecture can be used to implement enhanced security measures. For example, the external schema can be used to restrict access to certain data or to provide different views of the data to different users.
* **Improved performance:** The DBMS can optimize access to the data based on the information in the internal schema. This can improve the performance of application programs that access the database.
* **Data consistency:** The three-schema architecture helps to maintain data consistency by ensuring that all external schemas are derived from the same conceptual schema.
* **Support for database evolution:** The three-schema architecture makes it easier to evolve the database over time. For example, new entities and attributes can be added to the conceptual schema without affecting the existing external schemas or application programs.

## Example

Consider a database of student information. The external schema for a student registration system might include entities such as student, course, and enrollment. The attributes for the student entity might include name, address, and phone number. The attributes for the course entity might include course number, course name, and instructor. The attributes for the enrollment entity might include student ID, course number, and grade.

The conceptual schema for the student information database might include the same entities and attributes as the external schema, but it might also include additional entities and attributes that are not relevant to the student registration system. For example, the conceptual schema might include entities such as department and faculty members. The conceptual schema might also include attributes such as GPA and major.

The internal schema for the student information database would define how the data is physically stored in the database. For example, the internal schema might define a table for each entity, and it might define indexes on certain attributes to improve performance.

The three-schema architecture allows different users to have different views of the same data. For example, a student registration system might only need to access the student, course, and enrollment entities. A faculty member might also need to access the department and faculty member entities. The database administrator might need to access all of the entities and attributes in the database.

The three-schema architecture also makes it easier to evolve the database over time. For example, if a new course is added to the curriculum, the conceptual schema can be updated to include the new course. The external schema for the student registration system can then be updated to include the new course, without affecting the existing application programs.

The three-schema architecture is a powerful framework for designing and implementing database systems. It provides a number of benefits, including data independence, modular development, enhanced security, improved performance, data consistency, and support for database evolution.
