# Protobuf Schemas

This repository centralizes Protocol Buffer schemas and generated code for all microservices. It is designed to support API versioning and independent service definitions.

## Directory Structure

The repository is organized by service and version. Schema files are kept in a `proto` directory, and generated language files are placed in their respective language directories.

```text
.
├── .github/workflows/proto.yml
├── go.mod
└── users
    └── v1
        ├── proto
        │   ├── services.proto
        │   └── users.proto
        └── go
            ├── services_grpc.pb.go
            └── users.pb.go


