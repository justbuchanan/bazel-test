cc_library(
    name = "mylib",
    srcs = ["lib.cpp"],
    hdrs = ["lib.hpp"],
)

cc_binary(
    name = "myprog",
    srcs = ["main.cpp"],
    deps = [":mylib"],
)

cc_test(
    name = "mytest",
    srcs = ["test.cpp"],
    deps = [
        "mylib",
        "@com_google_googletest//:gtest_main",
    ],
)
