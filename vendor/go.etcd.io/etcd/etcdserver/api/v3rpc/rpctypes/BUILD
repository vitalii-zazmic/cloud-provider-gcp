load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "doc.go",
        "error.go",
        "md.go",
        "metadatafields.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/go.etcd.io/etcd/etcdserver/api/v3rpc/rpctypes",
    importpath = "go.etcd.io/etcd/etcdserver/api/v3rpc/rpctypes",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/google.golang.org/grpc/codes:go_default_library",
        "//vendor/google.golang.org/grpc/status:go_default_library",
    ],
)
