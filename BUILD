cc_binary(
    name = "hello",
    srcs = ["hello-world.cc"]
)

cc_binary(
    name = "hello-tflite",
    srcs = ["hello-tflite.cc"],
    deps = [
        "@org_tensorflow//tensorflow/lite:builtin_op_data",
        "@org_tensorflow//tensorflow/lite/kernels:builtin_ops",
        "@org_tensorflow//tensorflow/lite:framework",
    ],
)