load("@rules_cc//cc:defs.bzl", "cc_library", "cc_test")

cc_library(
    name = "hello-time",
    srcs = ["hello-time.cc"],
    hdrs = ["hello-time.h"],
    visibility = ["//main:__pkg__"],
)
cc_test(
    name = "hello-time-test",
    srcs = ["hello-time-test.cc"],
    deps = [
        ":hello-time",
        "@googletest//:gtest_main",
    ],
)
