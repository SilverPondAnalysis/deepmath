# Miscellaneous deepmath utilities

package(
    default_visibility = ["//visibility:public"],
)

licenses(["notice"])  # Apache 2.0

py_library(
    name = "model_utils",
    srcs = ["model_utils.py"],
    srcs_version = "PY2AND3",
    deps = [
        "@org_fold//tensorflow_fold/public:loom",
        "@org_tensorflow//tensorflow:tensorflow_py",
        "@org_tensorflow//third_party/py/numpy",
    ],
)

py_test(
    name = "model_utils_test",
    srcs = ["model_utils_test.py"],
    srcs_version = "PY2AND3",
    deps = [
        ":model_utils",
        "@org_tensorflow//tensorflow:tensorflow_py",
        "@org_tensorflow//third_party/py/numpy",
    ],
)

py_library(
    name = "dfile",
    srcs = ["dfile.py"],
    srcs_version = "PY2AND3",
    deps = [
        "@org_tensorflow//tensorflow:tensorflow_py",
    ],
)

py_test(
    name = "dfile_test",
    srcs = ["dfile_test.py"],
    srcs_version = "PY2AND3",
    deps = [
        ":dfile",
    ],
)
