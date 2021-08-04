load("@rules_java//java:defs.bzl", "java_binary")

java_binary (
    name = "BazelApp",
    main_class = "example.Main",
    srcs = glob(["java/**/*.java"]),
    deps = [
      "@maven//:commons_codec_commons_codec",
    ],
)
