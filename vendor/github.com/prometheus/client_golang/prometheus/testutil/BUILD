load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "testutil",
    srcs = [
        "lint.go",
        "testutil.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/github.com/prometheus/client_golang/prometheus/testutil",
    importpath = "github.com/prometheus/client_golang/prometheus/testutil",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/davecgh/go-spew/spew",
        "//vendor/github.com/prometheus/client_golang/prometheus",
        "//vendor/github.com/prometheus/client_golang/prometheus/internal",
        "//vendor/github.com/prometheus/client_golang/prometheus/testutil/promlint",
        "//vendor/github.com/prometheus/client_model/go",
        "//vendor/github.com/prometheus/common/expfmt",
    ],
)
