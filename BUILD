android_binary (
  name = "android",
  srcs = glob(["Calculator/src/**/*.java"]),
  custom_package = "com.android.calculator200",
  manifest = "Calculator/AndroidManifest.xml",
  resource_files = glob(["Calculator/res/**/*"]),
  deps = ["//external:android/appcompat_v4", "//external:android/appcompat_v7", 'arity'],
)

java_import (
  name = "arity",
  jars = ["Calculator/arity-2.1.2.jar"],
)