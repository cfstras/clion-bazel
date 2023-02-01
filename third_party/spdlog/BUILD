licenses(["notice"])

cc_library(
    name = "spdlog",
    srcs = glob([
        "src/**/*.cpp",
    ]),
    hdrs = glob([
        "include/**/*.h",
    ]),
    copts = ["-w"],
    defines = [
        "SPDLOG_COMPILED_LIB",
        "SPDLOG_FMT_EXTERNAL",
    ],
    includes = ["include"],
    visibility = ["//visibility:public"],
    deps = [
        "@fmt",
    ],
)
