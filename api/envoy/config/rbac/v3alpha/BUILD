licenses(["notice"])  # Apache 2

load("@envoy_api//bazel:api_build_system.bzl", "api_proto_package")

api_proto_package(
    deps = [
        "//envoy/api/v3alpha/core:pkg",
        "//envoy/api/v3alpha/route:pkg",
        "//envoy/type/matcher:pkg",
        "@com_google_googleapis//google/api/expr/v1alpha1:syntax_proto",
    ],
)
