load("@rules_cc//cc:defs.bzl", "cc_import")

cc_library(
    name = "gcc",
    includes = [
        "10.4.0/include",
        "10.4.0/include-fixed"
    ],
    deps = ["gcc_import"],
    visibility = ["//visibility:public"],
)

cc_import(
    name = "gcc_import",
    hdrs = glob([
      "10.4.0/include/**/*.h",
      "10.4.0/include-fixed/**/*.h"
    ]),
    visibility = ["//visibility:private"],
)
