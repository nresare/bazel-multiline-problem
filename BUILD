java_binary(
  name = "test",
  srcs = ["Hello.java"],
    deps = [
        ":with-multiline",
    ],
    main_class = "Hello",
)

java_library(
    name = "with-multiline",
    srcs = glob(["Multiline.java"]),
    visibility = ["//visibility:public"],
)
