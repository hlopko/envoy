load("@envoy_api//bazel:api_build_system.bzl", "api_proto_library_internal", "api_proto_package")

licenses(["notice"])  # Apache 2

api_proto_package(
    deps = ["//envoy/api/v3alpha/core"],
)

api_proto_library_internal(
    name = "client_ssl_auth",
    srcs = ["client_ssl_auth.proto"],
    deps = ["//envoy/api/v3alpha/core:address"],
)
