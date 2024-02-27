load("@rules_cc//cc:defs.bzl", "cc_library")

cc_library(
    name = "nvblox",
    srcs = glob(["src/**/*.cpp, src/**/*.cu"]),
    hdrs = glob(["include/nvblox/**/*.h"]),
    deps = [
        "@rules_cuda//cuda:runtime",
        "@com_github_gflags_gflags//:gflags",
        "@com_github_google_glog//:glog",
    ]
)
