package(
    default_visibility = ["//tensorflow:internal"],
    licenses = ["notice"],  # Apache 2.0
)

py_library(
    name = "risc_grad",
    srcs = ["risc_grad.py"],
    srcs_version = "PY2AND3",
    deps = [
        "//tensorflow/python:framework_ops",
    ],
)

py_library(
    name = "risc_ops",
    srcs = ["risc_ops.py"],
    srcs_version = "PY2AND3",
    deps = [
        "//tensorflow/python:risc_ops_gen",
    ],
)
