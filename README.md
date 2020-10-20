## Software Delivery Cycle

A software development life cycle (SDLC) model is a conceptual framework describing all activities in a software development project from planning to maintenance.


•	SDLC encompasses: planning, implementation, testing, documentation, deployment and maintenance.

•	Models shifted from traditional staged SDLC processes, to agile, and then to Devops.

•	Agile and Devops as practices merged traditional staging in new and interesting ways

•	The cloud brought the arrival of web-delivered resources into the picture.

•	Although SDLC is now much changed, the concept remains largely the same.

Phase 1: Planning

In the planning phase, project goals are determined and a high-level plan for the intended project is established. 
1.	      Identification of the system for development
2.	      Feasibility assessment
3.	      Creation of project plan

Phase 2: Analysis

In the analysis phase, end user business requirements are analyzed and project goals converted into the defined system functions that the organization intends to develop. 
1.	      Gathering business requirement
2.	      Creating process diagrams
3.	      Performing a detailed analysis

Phase 3: Design

In the design phase, we describe the desired features and operations of the system. This phase includes business rules, pseudo-code, screen layouts, and other necessary documentation. The two primary activities involved in the design phase are as follows:
1.	      Designing of IT infrastructure
2.	      Designing of system model

Phase 4: Development

In the development phase, all the documents from the previous phase are transformed into the actual system. The two primary activities involved in the development phase are as follows:
1.	      Development of IT infrastructure
2.	      Development of database and code

Phase 5: Testing

In the testing phase, all the pieces of code are integrated and deployed in the testing environment. Testers then follow Software Testing Life Cycle activities to check the system for errors, bugs, and defects to verify the system’s functionalities work as expected or not, often. The two primary activities involved in the testing phase are as follows:
1.	   Writing test cases
2.	   Execution of test cases

Phase 6: Deployment

During this next phase, the system is deployed to a real-life (the client’s) environment where the actual user begins to operate the system. All data and components are then placed in the production environment. This phase is also called referred to as ‘delivery.’

Phase 7: Maintenance

In the maintenance phase, any necessary enhancements, corrections, and changes will be made to make sure the system continues to work, and stay updated to meet the business goals. It is necessary to maintain and upgrade the system from time to time so it can adapt to future needs. The three primary activities involved in the maintenance phase are as follows:
1.	      Support the system users
2.	      System maintenance
3.	      System changes and adjustment



## Test Driven Development
Test Driven Development (TDD) in simple terms, test cases for each functionality are created and tested first and if the test fails then the new code is written in order to pass the test and making code simple and bug-free.

Basically, TDD is use to write and correct the failed tests before writing new code (before development). This helps to avoid duplication of code as we write a small amount of code at a time in order to pass tests. (Tests are nothing but requirement conditions that we need to test to fulfill them).

How to perform TDD test: 
1.	Add a test.
2.	Run all tests and see if any new test fails.
3.	Write some code.
4.	Run tests and Refactor code.
5.	Repeat.



## Continuous Integration

Continuous Integration (CI) is the process of automating the build and testing of code every time a team member commits changes to version control. CI encourages developers to share their code and unit tests by merging their changes into a shared version control repository after every small task completion.

Teams use build definitions to ensure that every commit to the master branch triggers the automated build and testing processes.  Implementing CI this way ensures bugs are caught earlier in the development cycle, which makes them less expensive to fix.  Automated tests run for every build to ensure builds maintain a consistent quality



## Continuous Delivery

Continuous Delivery is basically ensuring your codebase is ready to deploy safely at any point in time. Deployments include all changes associated with new features, bug fixes and features in the early stages of development which can be enabled using feature flags for target users to test in their production environments.

Continuous delivery is the next step in the process where the tested code from continuous integration is automatically deployed in various environments by a manual trigger.


## Configuration Management
Configuration management (CM) focuses on establishing and maintaining consistency of a product's performance, and its functional and physical attributes with its requirements, design, and operational information throughout its life.

A configuration management tool can improve the organization's change-impact analysis, reducing the outages caused by production changes. Without configuration management in place, it is nearly impossible to understand the impact of any changes to an environment.

Configuration management combines valid service models, CI interdependency mapping and correlations made between CIs and requests for changes to help restore services faster during an outage.


## Containerization

Containerization is the process of packaging an application along with its required libraries, frameworks, and configuration files together so that it can be run in various computing environments efficiently. In simpler terms, containerization is the encapsulation of an application and its required environment.


## Cloud Scalability, and Reliability

Scalability is the capability of a process, network, software or appliance to grow and manage increased demands. Through scalability you can scale up your data storage capacity or scale it down to meet the demands of your growing business.

Reliability is the most important feature of any application, because if the application is not reliable, users will eventually leave, and the other features won't matter.

•	An application must have measurable reliability goals, and deviations must be promptly corrected.

•	The application must be architected for scalability, high availability, and automated change management.

•	The application must be self-healing where possible, and it must be instrumented for observability.

•	The operational procedures used to run the application must impose minimal manual work and cognitive load on operators, while ensuring rapid mitigation of failures.



## Software Architecture / Software Architecture Patterns

Software architecture is taking the characteristics of the software and converting it into a structured solution that fulfills your business needs and technical requirements. These characteristics include things like scalability, reusability, flexibility, and many other traits.

The complexity of recent software solutions is continuously going up due to the continued evolution of the business expectations. With complex software, not only does the software development activity become very difficult, but also the software maintenance and enhancement tasks become tedious and time-consuming. Software patterns come as a soothing factor for software architects, developers, and operators.

Note - The patterns will address issues such as minimizing the business risk, maintaining high availability, and many others. Please keep in mind that the decision on which architecture to use will depend on your unique requirements.

Top architecture patterns

Layered pattern: 

This pattern will be useful in creating something that can be broken down into subtasks, and all of them are at a certain level of abstraction. This type of software system architecture is often used in desktop apps and e-commerce web apps.

Client-server pattern:

The way it works is the server supplies the client component with services the client needs from the server, and the later will give the right one to those clients. You will encounter such programming architectures in some of the online apps you use every day, such as email and file-sharing services.

Master-slave pattern:

The master component will distribute all the jobs to the slave components and calculate the ultimate result from whatever the slaves have compiled. Such architectural patterns are used in database replication and connecting peripherals to a bus.

Pipe-filter pattern:

If you are looking to create a system that produces and process streams of data, this would be a good one to choose. Individual processing steps are contained inside a filter, and the data that needs to be processed flows through the pipes. You can use these pipes to buffer or synchronize the data. Good examples of this architecture can be found in data compilers bioinformatic workflows.

Peer to peer pattern:

All the separate components are called “peers.” They may function like a client that requests the peers to perform a particular function or as a server that provides the peers with everything they need. The role of the peer may change over time. This sort of pattern is common among file-sharing networks.

Event-bus pattern:

Unlike some of the other patterns on this list, this one has four entities: bus, listener, source, and channel. The sources send messages to certain channels on the event bus, while the listeners will tune in to channels they need. The listeners will be notified when a message was published to a channel to which they are tuned in. This sort of architecture is widespread in Android apps and various notification services.




## Client-Server

The client-server model, or client-server architecture, is a distributed application framework dividing tasks between servers and clients, which either reside in the same system or communicate through a computer network or the Internet. The client relies on sending a request to another program in order to access a service made available by a server. The server runs one or more programs that share resources with and distribute work among clients. 

Client requests are organized and prioritized in a scheduling system, which helps servers cope in the instance of receiving requests from many distinct clients in a short space of time. The client-server approach enables any general-purpose computer to expand its capabilities by utilizing the shared resources of other hosts. Popular client-server applications include email, the World Wide Web, and network printing.


Some haracteristics of Client/Server Architecture:

•	Asymmetrical protocols-There is a many-to-one relationship between clients and a server. Clients always initiate a dialog by requesting a service. Servers wait passively for requests from clients.

•	Encapsulation of services-The server is a specialist: when given a message requesting a service, it determines how to get the job done. Servers can be upgraded without affecting clients as long as the published message interface used by both is unchanged.

•	Integrity-The code and data for a server are centrally maintained, which results in cheaper maintenance and the protection of shared data integrity. At the same time, clients remain personal and independent.

•	Location transparency-The server is a process that can reside on the same machine as a client or on a different machine across a network. Client/server software usually hides the location of a server from clients by redirecting service requests. A program can be a client, a server, or both.

•	Scalability-Client/server systems can be scaled horizontally or vertically. Horizontal scaling means adding or removing client workstations with only a slight performance impact. Vertical scaling means migrating to a larger and faster server machine or adding server machines.

Every client/server application contains three functional units:

•	Presentation logic or user interface (for example, ATM machines)

•	Business logic (for example software that enables a customer to request an account balance)

•	Data (for example, records of customer accounts)

In 2-tier client/server applications, the business logic is buried inside the user interface on the client or within the database on the server in the form of stored procedures. Alternatively, the business logic can be divided between the client and server. File servers and database servers with stored procedures are examples of 2-tier architecture.

In 3-tier client/server applications, the business logic resides in the middle tier, separate from the data and user interface. In this way, processes can be managed and deployed separately from the user interface and the database. Also, 3-tier systems can integrate data from multiple sources.




## Peer-to-Peer

Peer-to-peer meaning is the direct interaction between two computer systems within one network. Files can be shared directly between systems on the network without the need of a central server. In other words, each computer on a P2P network becomes a file server as well as a client. 

It is very common to see P2P network systems on local area networks, such as home networks, where each device can be synced with one another to share files. These systems can be created as wired or wireless networks where they use the same networking protocols as well as the same software to perform their functions. Schools and small businesses regularly take advantage of creating a P2P network system to share and access files among all users.

Advantages:

•	Security. Each node of the network holds information about the whole system. Even if a part of the system is attacked or blocked others can keep the rest of it alive.

•	Speed. Speed is an interesting peculiarity of this kind of networks. The more peers participate in the network the faster it gets.

•	Independence. Since each computer of the network acts on its own, it does not depend on the other participants.


Disadvantages:

•	Updating. The P2P network cannot be updated entirely at once. Each part of it updates on its own. Thus, it may take quite a long time and a lot of computing power.

•	Back up. There is no central server that may have a backup. Each node makes a backup on its own.

•	Lack of control. Peer-to-peer networks are used not only in cryptocurrency. Some fields require a certain control. However, the distributed network is very difficult to control. The lack of control may raise some problems such as illegal activity.



## Monolithic

The Monolithic application describes a single-tiered software application in which different components combined into a single program from a single platform.

 Components can be:

•	Authorization — responsible for authorizing a user

•	Presentation — responsible for handling HTTP requests and responding with either HTML or JSON/XML (for web services APIs).

•	Business logic — the application’s business logic.

•	Database layer — data access objects responsible for accessing the database.

•	Application integration — integration with other services (e.g. via messaging or REST API). Or integration with any other Data sources.

•	Notification module — responsible for sending email notifications whenever needed.


Benefits:

•	Simple to develop — At the beginning of a project it is much easier to go with Monolithic Architecture.

•	Simple to test. For example, you can implement end-to-end testing by simply launching the application and testing the UI with Selenium.

•	Simple to deploy. You have to copy the packaged application to a server.

•	Simple to scale horizontally by running multiple copies behind a load balancer.


Drawbacks:

•	Maintenance — If Application is too large and complex to understand entirely, it is challenging to make changes fast and correctly.

•	The size of the application can slow down the start-up time.

•	You must redeploy the entire application on each update.

•	Monolithic applications can also be challenging to scale when different modules have conflicting resource requirements.

•	Reliability — Bug in any module (e.g. memory leak) can potentially bring down the entire process. Moreover, since all instances of the application are identical, that bug impact the availability of the entire application




##  Microservices

Microservices are an approach to application development in which a large application is built as a suite of modular services (i.e. loosely coupled modules/components). Each module supports a specific business goal and uses a simple, well-defined interface to communicate with other sets of services.

Instead of sharing a single database as in Monolithic application, each microservice has its own database. Having a database per service is essential if you want to benefit from microservices, because it ensures loose coupling. Each of the services has its own database. 


Benefits:

•	Microservices Enables the continuous delivery and deployment of large, complex applications.

•	Better testability — services are smaller and faster to test.

•	Better deployability — services can be deployed independently.

•	It enables you to organize the development effort around multiple teams. Each team is responsible for one or more single service. Each team can develop, deploy and scale their services independently of all of the other teams.

•	Improved fault isolation. For example, if there is a memory leak in one service then only that service is affected. The other services continue to handle requests.

Drawbacks:

•	Developers must deal with the additional complexity of creating a distributed system.

•	Implementing use cases that span multiple services requires careful coordination between the teams.

•	Deployment complexity. In production, there is also the operational complexity of deploying and managing a system comprised of many different service types.


 
##  REST 

REST stands for REpresentational State Transfer. It means when a RESTful API is called, the server will transfer to the client a representation of the state of the requested resource.

REST is a client-server architecture. The client and the server both have a different set of concerns. The server stores and/or manipulates information and makes it available to the user in an efficient manner. The client takes that information and displays it to the user and/or uses it to perform subsequent requests for information. This separation of concerns allows both the client and the server to evolve independently as it only requires that the interface stays the same.


A RESTful web application exposes information about itself in the form of information about its resources. It also enables the client to take actions on those resources, such as create new resources (i.e. create a new user) or change existing resources (i.e. edit a post).

In order for your APIs to be RESTful, you have to follow a set of constraints when you write them. For example, when a developer calls Instagram API to fetch a specific user (the resource), the API will return the state of that user, including their name, the number of posts that user posted on Instagram so far, how many followers they have, and more.
The representation of the state can be in a JSON format, and probably for most APIs this is indeed the case. It can also be in XML or HTML format.

What the server does when you, the client, call one of its APIs depends on 2 things that you need to provide to the server:

1.	An identifier for the resource you are interested in. This is the URL for the resource, also known as the endpoint. In fact, URL stands for Uniform Resource Locator.

2.	The operation you want the server to perform on that resource, in the form of an HTTP method, or verb. The common HTTP methods are GET, POST, PUT, and DELETE.







DynamoDB:

DynamoDB is a fully managed, Internet scalable, easily administrated and cost-effective NoSQL database.

Start with AWS.py file, use a class method, initialize, add Table name, boto3, DB, and columns including items that you will need for your project. 
For example, 

Class Blog:
    def __init__(self):
        self.__Tablename__ = "DevBops_blog"
        self.client = boto3.client('dynamodb')
        self.DB = boto3.resource('dynamodb')
        self.Primary_Column_Name = "blogName"
        self.Primary_key = "blogName"
        self.columns = ["BlogDate", "BlogTime", "UserName", "BlogContent", "BlogLocation", "BlogComment"]
        self.table = self.DB.Table(self.__Tablename__)

if __name__ == "__main__":
    blog = Blog()

Use CURD functions to add, create, delete, update, and view the data. 

Response template: 
return {
               "Result": False or True,
               "Error": None or errorMessage,
               "Description": "",
               "BlogID": None or blogID
           }


Example:


def delete(self, BlogName):
        response = self.table.scan(
            FilterExpression=Attr("blogName").eq(BlogName)
        )
        if response["Items"]:
             self.Primary_key = response["Items"][0]["blogName"]
             res = self.table.delete_item(
                 Key={
                     self.Primary_Column_Name:self.Primary_key
                 }
             )
             return {
                 "Result": True,
                 "Error": None,
                 "Description": "Blog was deleted"
             }
        else:
            return {
                "Result": False,
                "Error": "Blog does not exists",
                "Description": "Error"
            }

What is REST?

REST (i.e. Representation State Transfer) is an architectural style for defining our routes. It is a way of mapping HTTP routes and the CRUD functionalities.

What are routes?
Routes are the code that are responsible for listening and receiving requests and then deciding what to send back.
What is CRUD?
When building APIs, we want to provide the four basic types of functionality. There must be a way to Create, Read, Update, and Delete resources.

### Rest API:
REST API is composed of three key items: (1) the url& endpoint, (2) the method, and (3) the data.

When a client makes an HTTP request against an API in order to retrieve data, the first item that must be designed is the URL. The URL generally encompasses the sites domain, a series of directory hierarchies, and finally the endpoint

There are four main methods that are generally used when making requests with a REST API: GET, POST, PUT, and DELETE. 

The main takeaway is that data can be retrieved, added, or deleted from any given database using these methods. 

GET requests are the most common type of request mainly used to retrieve data from a server or database. 

POST requests are used to send data to an API in order to create or update an entry. 

PUT requests are used to send data to an API in order to create or update an entry. (However, PUT requests are idempotent, meaning that the application of this method multiple times can be done without changing the final result).

DELETE requests are used to delete certain entries within the database.


### Creating the Flask Application:

Flask’s the main focus within APIs concerns the routing and flow of information.

We begin the process by importing flask and necessary connecting files, defining our ‘app’ within the init.py / blog.py file and creating a Flask application. 

app = flask.Flask(__name__)
app.config["DEBUG"] = True

We then must create a few functions that display data when certain routes are taken within the URL. 
For example, ‘view all’ function which displays all entries within the database. 


@app.route('/view', methods=["GET"])

def viewing():
    res = blog.view()
    return res

With this functionality enabled, end-users are now able to query all of the data within our database. 

Once all the routes snd functions are completed,
the application can be run using Flask’s run functionality.

app.run()


## Postman:

Postman is a collaboration platform for API development. It is a popular API client and it enables you to design, build, share, test, and document APIs.
Using the Postman tool, we can send HTTP/s requests to a service, as well as get their responses. By doing this we can make sure that the service is up and running.

What is HTTP?

HTTP stands for Hyper Text Transfer Protocol. HTTP enables communication between clients and servers. Clients are often web browsers and Servers are often computers on the cloud.
If a client submits an HTTP request to the server, then the server returns a response to the client. The response sent by the server contains status information about the request and the requested content.


Most commonly used HTTP methods are as follows:
1. GET:  method is used to retrieve data from an API.
2. POST: method is used to send new data to an API
3. PUT: method is used to update existing data
4. PATCH: method is used to update existing data
5. DELETE : method is used to remove existing data.


Testing Get Requests:

GET is used to request data from a specified resource. Once the new request is chosen as a GET request in the tool, proceed to name the request. Next, mention the URL to be tested.

Once the request is saved, send the request by clicking the Send button. As a result, the response body is displayed in the lower section of the Workspace. The response body is the result of the API request being sent. To validate this result of the GET request, view the response text, Status, Time Taken, Size in that section.


Testing Post Requests:

POST is used to send data to a server to create/update a resource. To create a POST request, we follow similar steps as we did for the GET request creation. However, this time choose the POST option for the URL. We also mention the data to be created or updated in the Request Body section. After that, we click the Save button and send the request by clicking the Send button.






