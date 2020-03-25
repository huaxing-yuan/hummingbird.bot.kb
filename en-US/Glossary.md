# KB Glossary

### Automated Test
A test that is configured in test automation tool, and can be executed by the tool.

### Extension Designer
Extension Designer is a module to import and configure service descriptions, from WSDL or Swagger documentation.

### HTTP
The Hypertext Transfer Protocol (HTTP) is an application protocol for distributed, collaborative, hypermedia information systems. HTTP is the foundation of data communication for the World Wide Web, where hypertext documents include hyperlinks to other resources that the user can easily access, for example by a mouse click or by tapping the screen in a web browser. 

### OpenAPI
The OpenAPI Specification, originally known as the Swagger Specification, is a specification for machine-readable interface files for describing, producing, consuming, and visualizing RESTful web services. Originally part of the Swagger framework, it became a separate project in 2016, overseen by the OpenAPI Initiative, an open-source collaboration project of the Linux Foundation. Swagger and some other tools can generate code, documentation and test cases given an interface file. 

See also: Swagger

### Swagger
Swagger is an open-source software framework backed by a large ecosystem of tools that helps developers design, build, document, and consume RESTful web services. While most users identify Swagger by the Swagger UI tool, the Swagger toolset includes support for automated documentation, code generation, and test-case generation. 

See also: OpenAPI

### SOAP
SOAP (abbreviation for Simple Object Access Protocol) is a messaging protocol specification for exchanging structured information in the implementation of web services in computer networks. Its purpose is to provide extensibility, neutrality and independence. It uses XML Information Set for its message format, and relies on application layer protocols, most often Hypertext Transfer Protocol (HTTP).

### Service Simulation
Service simulation is a functionality to simulate services which application depends on. 

It gives a way to simulate different kind of replies in order to test how application behaves to these replies. 

### Test Automation
An activity to build, configure and script test cases within an automation tool, in order to produce automated tests.
These automated tests can be executed and verified by the tool

### Test Runner
An integrated user interface with all necessary functions to run manual API Testing, such as calling an API under test, simulates an underlying API

### Virtual Service
A service that is virtualized by the service simulation engine. You may control the reply of the service to test how application behaves.

See also: Service Simulation

### WSDL
The Web Services Description Language (WSDL) is an XML-based interface description language that is used for describing the functionality offered by a web service.

#### Service (WSDL)
In WSDL, Service contains a set of system functions that have been exposed to the Web-based protocols. 

#### Endpoint (WSDL)
#### Port (WSDL)
In WSDL, Endpoint (or Port) defines the address or connection point to a Web service. It is typically represented by a simple HTTP URL string. 

#### PortType (WSDL)
#### Interface (WSDL)
In WSDL, PortType (or Interface) Defines a Web service, the operations that can be performed, and the messages that are used to perform the operation. 

#### Operation (WSDL)
In WSDL, Defines the SOAP actions and the way the message is encoded, for example, "literal." An operation is like a method or function call in a traditional programming language. 

#### Message (WSDL)
In WSDL, typically, a message corresponds to an operation. The message contains the information needed to perform the operation. Each message is made up of one or more logical parts. Each part is associated with a message-typing attribute. The message name attribute provides a unique name among all messages. The part name attribute provides a unique name among all the parts of the enclosing message. Parts are a description of the logical content of a message. In RPC binding, a binding may reference the name of a part in order to specify binding-specific information about the part. A part may represent a parameter in the message; the bindings define the actual meaning of the part. Messages were removed in WSDL 2.0, in which XML schema types for defining bodies of inputs, outputs and faults are referred to simply and directly. 

#### Types (WSDL)
In WSDL, Types Describes the data. The XML Schema language (also known as XSD) is used (inline or referenced) for this purpose. 

### XML
XML stands for Extensible Markup Language. It is a markup language that defines a set of rules for encoding documents in a format that is both human-readable and machine-readable.
XML is widely used as a standard of document and message format. SOAP Web Service uses also XML as document format.

For more information about XML, please refer to [XML Standard](https://www.w3.org/TR/xml/)

### XML Schema
### XSD
An XML Schema describes the structure of an XML document. The description of the schema is standarlised as XML Schema Definition (XSD).

For more information about XML Schema Definition Language, please refer to [XML Schema](https://www.w3.org/TR/xmlschema11-1/)

### JSON
JavaScript Object Notation (JSON) is an open standard file format, and data interchange format, that uses human-readable text to store and transmit data objects consisting of attribute–value pairs and array data types (or any other serializable value).

It usually uses less space than XML document but doesn't not contain metadata information, while XML document contains metadata by using `TAGS` and `ATTRIBUTES`  

### Extension Designer
Extension Designer is a component of Hummingbird used to import and organize service descriptions, such as WSDL and Swagger. Extension Designer generates object models from service description in order to give users an Object-Model based API testing experience.

### Regular Expression
### RegEx
A regular expression or regex is a sequence of characters that define a pattern. Usually such patterns are used by string searching algorithms for "find" or "find and replace" operations on strings.

In Hummingbird, you can use Regular Expression to match and assert test result.

### XPATH
XPath (XML Path Language) is a query language for selecting nodes from an XML document.

XPath is widely used in Assertions: it can be used verify test result from a XML based Web Service (such as SOAP Request or Response). against expected value.

See Also : JsonPath

### JSON PATH
### JsonPath
Similar to XPATH, Json Path is a query language for selecting nodes from a JSON document.

Json Path can be used in Assertions to verify test result from a JSON based REST Service against expected value

See Also: XPATH

### Assertion
An assertion is a predicate to a point in the test, that always should evaluate to true during test execution. False assertion means actual result is not expected and will fail the test.

In Hummingbird, There are different type of assertions are implemented that you can use to run automated checks.