# Java Projects Portfolio

A collection of Java projects covering core Java programming,
client-server networking, JDBC database connectivity, Java RMI, MVC
design, and Java Servlet web applications.
**Author:** Garvit Agarwal\
**Repository:** [Java --- GitHub]([https://github.com/garvit0555-GITJPR)

**Repository:** [garvit0555-GITJPR/Java](https://github.com/garvit0555-GITJPR/Java_lab)
## About This Repository

## Projects

  --------------------------------------------------------------------------------------------------
  Project                                                        Main learning areas
  -------------------------------------------------------------- -----------------------------------
  [JDBC](./JDBC/README.md)                                       Java Database Connectivity, SQL
                                                                 database access

  [MVCCalculator](./MVCCalculator/README.md)                     Model--View--Controller (MVC),
                                                                 separation of concerns

  [RMI](./RMI/README.md)                                         Java Remote Method Invocation,
                                                                 remote client-server calls

  [ShopSphere](./ShopSphere/README.md)                           Multi-module Java e-commerce
                                                                 application, persistence, services,
                                                                 networking and web UI

  [StudentRegistration](./StudentRegistration/README.md)         Java application with database
                                                                 connection and student records

  [java-tcp-client-server](./java-tcp-client-server/README.md)   TCP sockets, client-server
                                                                 communication
This repository brings together Java programming projects and practical
exercises in one place. The projects cover core Java, database
connectivity, client-server networking, MVC architecture, Java RMI, and
Java web development using Servlets/JSP. Each project is maintained in
its own folder so that its source code and supporting files remain
organized.

  [servlet](./servlet/README.md)                                 Java Servlet API, request/response
                                                                 handling, sessions, filters and
                                                                 listeners
> These are separate projects, not one application that runs with a
> single command. Follow the setup instructions inside each project
> before building or running it.

  [servlet-lab](./servlet-lab/README.md)                         Servlet-based web application with
                                                                 login/registration examples
  --------------------------------------------------------------------------------------------------
## Projects

## Repository structure
  --------------------------------------------------------------------------------------------
  Project                                      Description             Main concepts
  -------------------------------------------- ----------------------- -----------------------
  [Java TCP                                    Demonstrates            `Socket`,
  Client--Server](./java-tcp-client-server/)   communication between a `ServerSocket`,
                                               Java client and server  streams, networking
                                               using TCP sockets.      

  [JDBC](./JDBC/)                              Demonstrates Java       JDBC driver, database
                                               Database Connectivity   connection, SQL
                                               for connecting Java     
                                               code to a relational    
                                               database.               

  [JSP-Project](./JSP-Project/)                Java web project        JSP/Servlet web
                                               associated with the     development, Maven
                                               Servlet folder and      
                                               Maven configuration.    
                                               Review its project      
                                               README and source for   
                                               the exact implemented   
                                               functionality.          

  [MVC Calculator](./MVCCalculator/)           Organizes a calculator  MVC pattern, separation
                                               using separate model,   of concerns
                                               view, and controller    
                                               classes.                

  [RMI](./RMI/)                                Demonstrates remote     Remote interfaces, RMI
                                               method invocation using server/client
                                               Java client/server      
                                               classes.                

  [Servlet](./servlet/)                        Maven-based servlet     HTTP
                                               examples covering       requests/responses,
                                               request handling and    sessions, filters,
                                               common Servlet API      listeners
                                               concepts.               

  [Servlet Lab](./servlet-lab/)                A separate servlet lab  Servlet routing, web
                                               project with its own    application structure
                                               Maven configuration and 
                                               source tree.            

  [ShopSphere](./ShopSphere/)                  A multi-module Java     Modular design,
                                               project with common,    persistence,
                                               DAO, service, network,  networking, desktop/web
                                               RMI, Swing-admin, and   components
                                               web modules.            

  [Student                                     Java                    Java, JDBC/database
  Registration](./StudentRegistration/)        student-registration    setup, SQL
                                               project with database   
                                               connection code and an  
                                               SQL script.             
  --------------------------------------------------------------------------------------------

Descriptions above summarize the visible folder names and files. Confirm
exact features and supported operations by reviewing each project's
source code.

## Repository Structure

``` text
Java/
├── java-tcp-client-server/
├── JDBC/
├── JSP-Project/
│   ├── Servlet/
│   ├── jsp-project-README.md
│   └── pom.xml
├── MVCCalculator/
├── RMI/
├── ShopSphere/
├── StudentRegistration/
├── java-tcp-client-server/
├── servlet/
└── servlet-lab/
├── servlet-lab/
├── ShopSphere/
└── StudentRegistration/
```

Each folder is an independent learning project. Build and run projects
from their own directories; dependencies and execution steps are not
shared across the entire repository.
The tree is simplified to show the main project folders; each folder
contains its own source code and configuration files.

## Technologies and Concepts

## General requirements
Depending on the project, this repository provides practice with:

-   Install a JDK compatible with each project's source code and build
    configuration.
-   Install Git to clone the repository.
-   Install Maven for projects that contain a `pom.xml`.
-   Install and configure a supported SQL database for database-backed
    projects.
-   For servlet projects, use a servlet container compatible with the
    Servlet API version declared by the project's `pom.xml`.
-   Java classes, objects, and application entry points
-   Model--View--Controller (MVC) organization
-   JDBC and SQL database connectivity
-   TCP socket-based client-server communication
-   Java Remote Method Invocation (RMI)
-   Java Servlet/JSP web applications
-   Maven project configuration and packaging
-   Modular application structure and separation of responsibilities

Check each project's README and build files before running it. Database
names, credentials, ports, and server settings may need to be configured
for your own computer.
Check each project's `pom.xml`, source files, and README for the exact
Java version, dependencies, and configuration required.

## Clone the repository
## Requirements

Common requirements may include:

-   A compatible Java Development Kit (JDK)
-   Git
-   Apache Maven for projects containing a `pom.xml`
-   A compatible servlet container for web projects
-   A configured database and JDBC driver for database-backed projects

Not every project requires every tool. Review the project-specific
README before installation.

## Getting Started

Clone the repository:

``` bash
git clone https://github.com/anirudh7537/Java.git
cd Java
```

## How to use this repository
Then:

1.  Choose a project folder.
2.  Read its README and inspect its build/configuration files.
3.  Install only the dependencies required by that project.
4.  Configure local database credentials, ports, or server settings if
    needed.
5.  Build and run that project using its own instructions.

There is no single root-level command that runs every project.

## Academic Purpose and Learning Outcomes

This collection is intended to demonstrate practical learning across
Java programming and application development. It helps illustrate how
Java can be used for standalone programs, database-backed applications,
network communication, remote calls, and web applications.

For an academic review or viva, be prepared to explain each submitted
project's purpose, the role of its main classes, its execution steps,
and any limitations or configuration requirements.

## Documentation

Each project should have its own `README.md` containing:

-   Project overview and objectives
-   Technologies and prerequisites
-   Folder structure
-   Setup/build/run instructions
-   Explanation of the main classes or modules
-   Testing, limitations, and possible improvements

1.  Open the folder of the project you want to study.
2.  Read that project's README and inspect its source files.
3.  Configure any database or server dependency locally.
4.  Compile or build the project using the instructions in its README.
5.  Do not commit database passwords, private configuration, generated
    build output, or IDE-specific files.
For the JSP project, rename `JSP-Project/jsp-project-README.md` to
`JSP-Project/README.md` if it is intended to be the project's main
documentation file. If `Servlet/` is itself an independent project, add
a separate `README.md` inside that folder too.

## Learning outcomes
## Important Notes

This portfolio demonstrates practice with Java classes and interfaces,
separation of responsibilities, database access, network communication,
remote calls, web request handling, and modular application
organization.
-   Do not commit passwords, API keys, or private database credentials.
-   Generated files such as `.class` files and Maven `target/` output
    usually do not need to be committed; check each project's
    `.gitignore`.
-   Test build and run instructions on your own setup before presenting
    them.
-   The README documents the repository; it does not replace a
    demonstration of the actual working code.

## Notes
------------------------------------------------------------------------

This repository groups several independent projects; it is not one
application that starts with a single command. Some projects may be
coursework or demonstrations rather than production-ready software.
Review and test each project before using it in a real environment.
**Maintained by Garvit Agarwal**
