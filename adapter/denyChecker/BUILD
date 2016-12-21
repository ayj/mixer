package(default_visibility = ["//visibility:public"])

load("@io_bazel_rules_go//go:def.bzl", "go_library", "go_test")

go_library(
    name = "go_default_library",
    srcs = [
        "adapter.go",
        "builder.go",
    ],
    deps = [
        "//pkg/adapter:go_default_library",
    ],
)

go_test(
    name = "deny_checker_test",
    srcs = [ "builder_test.go" ],
    size = "small",
    deps = [ "//pkg/adaptertesting:go_default_library" ],
    library = ":go_default_library",
)