load("@envoy_api//bazel:api_build_system.bzl", "api_proto_package")

licenses(["notice"])  # Apache 2

api_proto_package(
    has_services = True,
    deps = [
        "//envoy/api/v2/auth:pkg",
        "//envoy/api/v2/cluster:pkg",
        "//envoy/api/v2/core:pkg",
        "//envoy/api/v2/endpoint:pkg",
        "//envoy/api/v2/listener:pkg",
        "//envoy/api/v2/ratelimit:pkg",
        "//envoy/api/v2/route:pkg",
        "//envoy/config/listener/v2:pkg",
        "//envoy/type:pkg",
    ],
)
