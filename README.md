# APIs development in go
Documentation, Tools, Frameworks/Kitq/Libs for APIs development in go.



## Monolith VS MicroService  :

 * https://threedots.tech/post/microservices-or-monolith-its-detail/
 * https://martinfowler.com/bliki/MonolithFirst.html

```
Almost all the cases where I’ve heard of a system that was built as a microservice system from scratch, 
it has ended up in serious trouble.

Almost all the successful microservice stories have started with a monolith that got too big and was broken up.

```
 
## Auth
 * https://threedots.tech/post/firebase-cloud-run-authentication/
 * [casbin](https://casbin.org/) : An authorization library that supports access control models like ACL, RBAC, ABAC



## APIs Design :

### Guides :

 *How To design APIs.*

* [Google API Design Guide](https://cloud.google.com/apis/design) : How to write API.
* [Google API Improvement Proposals](https://aip.dev) : Focused design documents for flexible API development.
* [Google linter for APIs](https://github.com/googleapis/api-linter) : A linter for APIs defined in protocol buffers.
* [Azure API Design](https://azure.github.io/azure-sdk/golang_design.html) : Go Guidelines: API Design.
* [Microsoft API Design](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design) : Web API design.
* [Microsoft API Guidelines](https://github.com/microsoft/api-guidelines/blob/vNext/Guidelines.md) :  API Guidelines.
* [Paypal API Style Guide](https://github.com/paypal/api-standards/blob/master/api-style-guide.md) : API Design Guidelines.
* [API Security Checklist](https://github.com/shieldfy/API-Security-Checklist) : Checklist of the most important security countermeasures.
* [APIsecurity](https://apisecurity.io/) : API Security Articles, News, Vulnerabilities & Best Practices.

* [API Evangelist](http://apievangelist.com/) : API Evangelist is a site dedicated to the technology, business, and politics of APIs.

### Diagrams :

 *Tools To design Architecture.*

* [go-diagrams](https://github.com/blushft/go-diagrams) : Go-Diagrams is a loose port of diagrams.
* [aws-icons-for-plantuml](https://github.com/awslabs/aws-icons-for-plantuml) : PlantUML sprites, macros, and other includes for Amazon Web Services services and resources.
* [plantuml](https://plantuml.com/) : PlantUML is a component that allows to quickly write diagrams.
* [The C4 model](https://c4model.com/) : The C4 model for visualising software architecture.

* [C4 PlantUML](https://github.com/RicardoNiepel/C4-PlantUML): C4-PlantUML combines the benefits of PlantUML and the C4 model for providing a simple way of describing and communicate software architectures.

## APIs specifications :

### REST
* [OpenAPIs](https://www.openapis.org/) : The OpenAPI Specification: a broadly adopted industry standard for describing modern APIs.

* [OpenAPI Spec 3.0.3](https://github.com/OAI/OpenAPI-Specification/blob/master/versions/3.0.3.md#infoObject) : OpenAPI spec V3 replace swagger V2.

### GraphQL

* [GraphQL](https://graphql.org/) : A query language for your API.

### gRPC

* [gRPC](https://grpc.io/) : A high-performance, open source universal RPC framework.
* [Protocol Buffers](https://github.com/protocolbuffers/protobuf) : Protocol Buffers - Google's data interchange format.
* [vscode-proto3](https://github.com/zxh0/vscode-proto3) : vscode extension for proto3.

* [grpcui](https://github.com/fullstorydev/grpcui) : grpcui is a command-line tool that lets you interact with gRPC servers via a browser.

## APIs Tools :

* [httpie](https://httpie.org/) : HTTP cli with an intuitive UI.
* [Insomnia](https://github.com/Kong/insomnia) : Cross-platform HTTP and GraphQL Client.
* [Postman](https://www.postman.com/) : Best Tool to test APIs (REST + GRAPHQL).
* [Postwoman](https://github.com/liyasthomas/postwoman) : A free, fast and beautiful API request builder.
* [OpenAPI Editor](https://editor.swagger.io/) : Best Tool to design OpenAPI spec online.
* [OpenAPI ReDoc UI](https://redoc.ly/redoc/) : Best Tool to visualize OpenAPI docs.
* [OpenAPI CLI](https://redoc.ly/openapi-cli/) : Validate & bundle OpenAPI definitions, with rich diagnostics..
* [OpenAPI VSCode](https://marketplace.visualstudio.com/items?itemName=42Crunch.vscode-openapi) : OpenAPI extension for Visual Studio Code.
* [PlantUML](https://plantuml.com/fr/) : Generate UseCase, Sequence Diagram.

## APIs traces/metrics :

* [OpenTelemetry](https://opentelemetry.io/) : OpenTelemetry provides a single set of APIs, libraries, agents, and collector services to capture distributed traces and metrics from your application.
* [OpenCensus](https://opencensus.io/) : OpenCensus is a set of libraries for various languages that allow you to collect application metrics and distributed traces. OpenCensus and OpenTracing have merged to form OpenTelemetry, which serves as the next major version of OpenCensus and OpenTracing.

* [Jaeger](https://www.jaegertracing.io/) : Jaeger: open source, end-to-end distributed tracing.

## APIs security :

* [ssllabs](https://www.ssllabs.com/ssltest/analyze.html) : SSL Server Test.

## Go Frameworks / Kits / Resources :

### Go Developer Roadmap :

* [Go Developer Roadmap](https://github.com/Alikhll/golang-developer-roadmap) : How to become a senior Go Developer.

### Documentation :

* [OWASP Go Secure Coding Practices](https://github.com/OWASP/Go-SCP) : Go programming language secure coding practices guide.

* [golang-tls](https://github.com/denji/golang-tls) : Simple Golang HTTPS/TLS Examples + Perfect SSL Labs Score with Go.

### AUTH :
 * [casbin](https://casbin.org/) : An authorization library that supports access control models like ACL, RBAC, ABAC

### SQL :

* [Gorm](https://gorm.io/) : The fantastic ORM library for Golang.
* [sqlmock](https://github.com/DATA-DOG/go-sqlmock) : Sql driver mock for Golang.

### Web Frameworks :

* [Beego](https://github.com/astaxie/beego) : Beego is used for rapid development of RESTful APIs, web apps and backend services in Go.
* [Buffalo](https://github.com/gobuffalo/buffalo) : Rapid Web Development w/ Go.
* [Echo](https://github.com/labstack/echo) : High performance, minimalist Go web framework.
* [Go-Kit](https://github.com/go-kit/kit) : A standard library for microservices.
* [Go Micro](https://github.com/micro/go-micro) : The Go Micro services development framework.
* [Gin](https://gin-gonic.com/) : Web Framework / API for Golang.
* [Cors](https://github.com/rs/cors) : Go net/http configurable handler to handle CORS requests.
* [Validator](https://github.com/go-playground/validator) : Go Struct and Field validation.

### OpenAPI :

* [oapi-codegen](https://github.com/deepmap/oapi-codegen) : Generate Go client and server boilerplate from OpenAPI 3 specifications.

### gRPC

* [protoc-gen-validate](https://github.com/envoyproxy/protoc-gen-validate) : protoc plugin to generate polyglot message validators.
* [go-grpc-middleware](https://github.com/grpc-ecosystem/go-grpc-middleware) : Golang gRPC Middlewares: interceptor chaining, auth, logging, retries and more.

### Security

* [gosec](https://github.com/securego/gosec) : Golang security checker.

### Test

* [Ginkgo](https://github.com/onsi/ginkgo/) : BDD Testing Framework for Go.
* [Testify](https://github.com/stretchr/testify) : Testify - Thou Shalt Write Tests.
* [Go Leak](https://github.com/uber-go/goleak) : Goroutine leak detector to help avoid Goroutine leaks.


## Container :

* [Docker](https://docs.docker.com/) : Docker Documentation.

* [Docker Compose](https://docs.docker.com/compose/) :  Docker Compose Documentation.

* [Container Structure Tests](https://github.com/GoogleContainerTools/container-structure-test) : A powerful framework to validate structure of a container image.

* [testcontainers-go](https://github.com/testcontainers/testcontainers-go) : Testcontainers is a Golang library that providing a friendly API to run Docker container.
