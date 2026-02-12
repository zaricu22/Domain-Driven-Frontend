# Domain-Driven-Frontend
Experimental sample of Onion architecture and Angular best practices


## Project Folder Structure
<pre>
├── core
│   ├── application
│   │   ├── dto
│   │   ├── event
│   │   ├── exception
│   │   ├── facade
│   │   ├── handler
│   │   ├── interface
│   │   ├── mapper
│   │   ├── security
│   │   ├── service
│   │   └── validation
│   └── domain
│       ├── aggregate
│       ├── entity
│       ├── event
│       ├── interface
│       │   ├── repository
│       │   └── unitofwork
│       ├── service
│       ├── shared
│       │   ├── constant
│       │   └── enum
│       ├── specification
│       └── valueobject
└── external
    ├── infrastructure
    │   ├── api
    │   ├── auth
    │   ├── interceptor
    │   ├── logging
    │   ├── messaging
    │   ├── persistence
    │   ├── storage
    │   └── util
    └── presentation
        ├── component
        ├── dialog
        ├── directive
        ├── guard
        ├── layout
        ├── page
        ├── pipe
        └── route
</pre>