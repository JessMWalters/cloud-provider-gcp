load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "gziphandler",
    srcs = [
        "gzip.go",
        "gzip_go18.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/github.com/NYTimes/gziphandler",
    importpath = "github.com/NYTimes/gziphandler",
    visibility = ["//visibility:public"],
)
