package(default_visibility = ["//visibility:public"])

load("@io_bazel_rules_go//go:def.bzl", "go_library", "go_test")

go_library(
    name = "go_default_library",
    srcs = [
        "manager.go",
    ],
    visibility = ["//visibility:public"],
    deps = [
        "//mixer/pkg/adapter:go_default_library",
        "//mixer/pkg/attribute:go_default_library",
        "//mixer/pkg/config:go_default_library",
        "//mixer/pkg/config/descriptor:go_default_library",
        "//mixer/pkg/config/proto:go_default_library",
        "//mixer/pkg/expr:go_default_library",
        "//mixer/pkg/status:go_default_library",
        "//pkg/log:go_default_library",        
        "@com_github_hashicorp_go_multierror//:go_default_library",
        "@io_istio_api//mixer/v1:go_default_library",
        "@io_istio_api//mixer/v1/config/descriptor:go_default_library",
    ],
)
