load("@envoy_api//bazel:api_build_system.bzl", "api_proto_library_internal", "api_proto_package")

licenses(["notice"])  # Apache 2

api_proto_package(
    deps = [
        "//envoy/api/v2/core",
        "//envoy/config/common/tap/v2alpha:pkg",
    ],
)

api_proto_library_internal(
    name = "tap",
    srcs = ["tap.proto"],
    deps = [
        "//envoy/api/v2/core:base",
        "//envoy/config/common/tap/v2alpha:common",
    ],
)
