package(default_visibility = ["//visibility:public"])

load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    testonly = 1,
    srcs = [
        "adapters.go",
    ],
    deps = [
        "//pkg/aspect:go_default_library",
        "//pkg/aspect/denyChecker:go_default_library",
        "//pkg/aspect/listChecker:go_default_library",
        "//pkg/aspect/logger:go_default_library",
        "//pkg/aspect/quota:go_default_library",
        "//pkg/registry:go_default_library",
    ],
)
