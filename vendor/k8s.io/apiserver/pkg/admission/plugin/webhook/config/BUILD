load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["kubeconfig.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/apiserver/pkg/admission/plugin/webhook/config",
    importpath = "k8s.io/apiserver/pkg/admission/plugin/webhook/config",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/apimachinery/pkg/runtime:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/runtime/serializer:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/util/runtime:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/util/validation/field:go_default_library",
        "//vendor/k8s.io/apiserver/pkg/admission/plugin/webhook/config/apis/webhookadmission:go_default_library",
        "//vendor/k8s.io/apiserver/pkg/admission/plugin/webhook/config/apis/webhookadmission/v1:go_default_library",
        "//vendor/k8s.io/apiserver/pkg/admission/plugin/webhook/config/apis/webhookadmission/v1alpha1:go_default_library",
    ],
)
