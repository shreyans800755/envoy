load("@envoy_api//bazel:api_build_system.bzl", "api_proto_package")

licenses(["notice"])  # Apache 2

api_proto_package(
    has_services = True,
    deps = [
        "//envoy/api/v3alpha/auth:pkg",
        "//envoy/api/v3alpha/cluster:pkg",
        "//envoy/api/v3alpha/core:pkg",
        "//envoy/api/v3alpha/endpoint:pkg",
        "//envoy/api/v3alpha/listener:pkg",
        "//envoy/api/v3alpha/ratelimit:pkg",
        "//envoy/api/v3alpha/route:pkg",
        "//envoy/config/listener/v3alpha:pkg",
        "//envoy/type:pkg",
    ],
)
