load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "term",
    srcs = ["term.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/component-base/term",
    importpath = "k8s.io/component-base/term",
    visibility = ["//visibility:public"],
    deps = ["//vendor/github.com/moby/term"],
)
