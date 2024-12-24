# load-tester
A fully-fledged load testing application with a structured design that adheres to SOC (Separation of Concerns), Go idiomatic principles, and simplicity.


## Directory Structure ##
load-tester/
├── cmd/
│   └── main.go        # Application entry point
├── internal/
│   ├── config/        # JSON parsing and configuration logic
│   ├── generator/     # Request generation and execution
│   ├── reporter/      # MongoDB integration for reports
│   └── web/           # HTTP server and report UI
├── static/            # Frontend assets for reports (e.g., HTML, CSS, JS)
├── go.mod             # Go module file
├── go.sum             # Dependency file
├── embedded/
│   └── requests.json  # Embedded JSON configuration
└── README.md
