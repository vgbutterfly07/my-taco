load("@build_bazel_rules_nodejs//:defs.bzl", "nodejs_binary", "http_server")

nodejs_binary(
    name = "www.my-taco.com",
    data = glob([
        "index.html",
        "js/*.js",
        "css/*.css",
        "fonts/**/*",
        "img/**/*",
    ]),
    entry_point = "index.html",
)

http_server(name = "server", data=[":www.my-taco.com"])
