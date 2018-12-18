package(default_visibility=["//visibility:public"])

load("@build_bazel_rules_nodejs//:defs.bzl", "rollup_bundle")

rollup_bundle(
    name = "js",
    srcs = glob([
        "*.js",
    ]),
    entry_point = "www.my-taco.com/js/main.js"
)
