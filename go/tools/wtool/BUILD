load("//go:def.bzl", "go_binary")

go_binary(
    name = "wtool",
    srcs = ["main.go"],
    visibility = ["//visibility:public"],
    deps = [
        "//go/tools/gazelle/rules:go_default_library",
        "//go/tools/gazelle/wspace:go_default_library",
        "@com_github_bazelbuild_buildifier//build:go_default_library",
        "@org_golang_x_tools//go/vcs:go_default_library",
    ],
)
