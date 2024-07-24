load("@build_bazel_rules_apple//apple:resources.bzl", "apple_core_data_model")

apple_core_data_model(
    name = "iOSAppCoreData", 
    srcs = glob(["TodoDataModel.xcdatamodeld/**"]),
    visibility = ["//visibility:public"]
)