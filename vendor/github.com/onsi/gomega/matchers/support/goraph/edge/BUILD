load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "edge",
    srcs = ["edge.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/github.com/onsi/gomega/matchers/support/goraph/edge",
    importpath = "github.com/onsi/gomega/matchers/support/goraph/edge",
    visibility = ["//visibility:public"],
    deps = ["//vendor/github.com/onsi/gomega/matchers/support/goraph/node"],
)
