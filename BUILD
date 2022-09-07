cc_library(
  name = "base16",
  srcs = ["libbase16.c"],
  hdrs = ["libbase16.h"],
)

cc_test(
  name = "base16_test",
  srcs = ["test_libbase16.c"],
  deps = [
    ":base16",
    "//testing/minunit",
  ],
)
