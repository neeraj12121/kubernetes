package(default_visibility = ["//visibility:public"])

licenses(["notice"])

load(
    "@io_bazel_rules_go//go:def.bzl",
    "go_library",
)

go_library(
    name = "go_default_library",
    srcs = ["interface.go"],
    tags = ["automanaged"],
    deps = [
        "//vendor/k8s.io/kube-apiextensions-server/pkg/client/informers/internalversion/apiextensions/internalversion:go_default_library",
        "//vendor/k8s.io/kube-apiextensions-server/pkg/client/informers/internalversion/internalinterfaces:go_default_library",
    ],
)
