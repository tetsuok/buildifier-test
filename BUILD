load("@com_github_bazelbuild_buildtools//buildifier:def.bzl", "buildifier")

buildifier(
    name = "buildifier",
    lint_mode = "warn",
)

cc_binary(
    name = "hello",
    srcs = ["hello.cc"],
)
