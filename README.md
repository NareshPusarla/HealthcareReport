# HelthcareReport

- Initially we create either a spring boot maven or gradle project for java.
- I had done this project as a maven project with required dependencies.

**Libraries used in Project:**
- Jackson
    - In software development, you have to process variously formatted data.
    - Either you have to load or save data in different formats, or you have to transfer data in various formats.
- Mockito
    - Unit/Integration testing is an integral part of the Software Development process. Often you want to test a single Class.
    - This ia an annotation based to connect with some classes to act as temporary database.
- AssertJ
    - AssertJ is the second library related to TDD in my list.
    - It offers a couple of static methods for test verification.
    - Rich set of assertions and helpful error messages.
- Hibernate
    - Domain model persistence for relational databases (ORM).
    - Domain model persistence for NoSQL data stores (OGM).
- Apache HTTPComponents
    - Low-level HTTP Transport Components for Client/Server services.
    - Offers both blocking and non-blocking I/O models. 
    - Synchronous HTTP Client for client-side authentication, state management, and connection management. 
    - Asynchronous HTTP Client to handle a high number of concurrent connections.

**Dependencies:**
- SwaggerUi and OpenApi-Ui for swagger.
- MySQL and Hibernate connector for database connection.
- JWT for security.
- Starter validation for validating entity fields.
- Lombok to generate getters and setters.
- Mockito and JUnit for testing purpose.

**Basic Project Class Files:**
- A repository and service class files for CRUD operations.
- A controller class is for implementation of declared service CRUD operations in AP format where a user navigation links will generate.
- Test cases will be written in other file.
- SQL connection details will be declared in Application.properties file.
- An entity class to declare all the fields require for project.
- A JWT class to write the necessary features to generate token.
- A swagger class to declare the documentation and comments that should be available in UI swagger presentation link.

**Annotations:**
- Annotations are declared with **@** symbol.
- Most used annotations are 
  - Rest Controller to trigger the controller class
  - Request Mapping to declare a default and static path
  - Service annotation to represent the service class
  - Autowired to connect a class within another class
  - Table annotation to say that entity class fields are table contents
  - Mockito to use testing features
  - Value annotation to set a value from other files using **$**
- API annotations are:
  - PostMapping
  - getMapping
  - PutMapping
  - DeleteMapping
