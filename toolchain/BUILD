package(default_visibility = ["//visibility:public"])

cc_toolchain_suite(
    name = "armhf_suite",
    toolchains = {
        "armhf": ":armhf_toolchain",
    },
)

load(":cc_toolchain_config.bzl", "cc_toolchain_config")
cc_toolchain_config(name = "armhf_toolchain_config")
filegroup(name = "empty")
cc_toolchain(
    name = "armhf_toolchain",
    toolchain_identifier = "armhf-toolchain",
    toolchain_config = ":armhf_toolchain_config",
    all_files = ":empty",
    compiler_files = ":empty",
    dwp_files = ":empty",
    linker_files = ":empty",
    objcopy_files = ":empty",
    strip_files = ":empty",
    supports_param_files = 0,
)





