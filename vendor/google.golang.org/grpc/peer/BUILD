load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "peer",
    srcs = ["peer.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/google.golang.org/grpc/peer",
    importpath = "google.golang.org/grpc/peer",
    visibility = ["//visibility:public"],
    deps = ["//vendor/google.golang.org/grpc/credentials"],
)
