java_test(
    name = "test",
    srcs = glob(["*.java"]),
    deps = [
        "@maven//:junit_junit",
        "//src/main/java/com/bmuschko/app/config:app-lib",
    ],
    test_class = "com.bmuschko.app.config.AllTests",
)