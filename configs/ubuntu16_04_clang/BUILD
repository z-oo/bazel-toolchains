# Copyright 2017 The Bazel Authors. All rights reserved.
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#    http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.

licenses(["notice"])  # Apache 2.0

package(default_visibility = ["//visibility:public"])

load("@bazel_toolchains//rules:docker_config.bzl", "docker_toolchain_autoconfig")
load(
    "@bazel_toolchains//rules:environments.bzl",
    "clang_env",
    "ubuntu16_04_clang_default_keys",
    "ubuntu16_04_clang_default_packages",
    "ubuntu16_04_clang_default_repos",
)

# Created on 2018.05.09
# Container: gcr.io/cloud-marketplace/google/clang-ubuntu@sha256:d553634f23f7c437ca35bbc4b6f1f38bb81be32b9ef2df4329dcd36762277bf7
docker_toolchain_autoconfig(
    name = "ubuntu16_04-clang-1.0-bazel_0.13.0-autoconfig",
    additional_repos = ubuntu16_04_clang_default_repos(),
    base = "@ubuntu16_04-clang//image",
    bazel_version = "0.13.0",
    env = clang_env(),
    keys = ubuntu16_04_clang_default_keys(),
    packages = ubuntu16_04_clang_default_packages(),
    tags = ["manual"],
    test = True,
)

# Created on 2018.05.09
# Container: gcr.io/cloud-marketplace/google/clang-ubuntu@sha256:d553634f23f7c437ca35bbc4b6f1f38bb81be32b9ef2df4329dcd36762277bf7
docker_toolchain_autoconfig(
    name = "msan-ubuntu16_04-clang-1.0-bazel_0.13.0-autoconfig",
    additional_repos = ubuntu16_04_clang_default_repos(),
    base = "@ubuntu16_04-clang//image",
    bazel_version = "0.13.0",
    env = clang_env() + {
        "BAZEL_LINKOPTS": "-lc++:-lc++abi:-lm",
    },
    keys = ubuntu16_04_clang_default_keys(),
    packages = ubuntu16_04_clang_default_packages(),
    tags = ["manual"],
    test = True,
)

# Created on 2018.06.08
# Container: gcr.io/cloud-marketplace/google/clang-ubuntu@sha256:d553634f23f7c437ca35bbc4b6f1f38bb81be32b9ef2df4329dcd36762277bf7
docker_toolchain_autoconfig(
    name = "ubuntu16_04-clang-1.0-bazel_0.14.1-autoconfig",
    additional_repos = ubuntu16_04_clang_default_repos(),
    base = "@ubuntu16_04-clang//image",
    bazel_version = "0.14.1",
    env = clang_env(),
    keys = ubuntu16_04_clang_default_keys(),
    packages = ubuntu16_04_clang_default_packages(),
    tags = ["manual"],
    test = True,
)

# Created on 2018.06.08
# Container: gcr.io/cloud-marketplace/google/clang-ubuntu@sha256:d553634f23f7c437ca35bbc4b6f1f38bb81be32b9ef2df4329dcd36762277bf7
docker_toolchain_autoconfig(
    name = "msan-ubuntu16_04-clang-1.0-bazel_0.14.1-autoconfig",
    additional_repos = ubuntu16_04_clang_default_repos(),
    base = "@ubuntu16_04-clang//image",
    bazel_version = "0.14.1",
    env = clang_env() + {
        "BAZEL_LINKOPTS": "-lc++:-lc++abi:-lm",
    },
    keys = ubuntu16_04_clang_default_keys(),
    packages = ubuntu16_04_clang_default_packages(),
    tags = ["manual"],
    test = True,
)

# Created on 2018.06.27
# Container: gcr.io/cloud-marketplace/google/clang-ubuntu@sha256:d553634f23f7c437ca35bbc4b6f1f38bb81be32b9ef2df4329dcd36762277bf7
docker_toolchain_autoconfig(
    name = "ubuntu16_04-clang-1.0-bazel_0.15.0-autoconfig",
    additional_repos = ubuntu16_04_clang_default_repos(),
    base = "@ubuntu16_04-clang//image",
    bazel_version = "0.15.0",
    env = clang_env(),
    keys = ubuntu16_04_clang_default_keys(),
    packages = ubuntu16_04_clang_default_packages(),
    tags = ["manual"],
    test = True,
)

# Created on 2018.06.27
# Container: gcr.io/cloud-marketplace/google/clang-ubuntu@sha256:d553634f23f7c437ca35bbc4b6f1f38bb81be32b9ef2df4329dcd36762277bf7
docker_toolchain_autoconfig(
    name = "msan-ubuntu16_04-clang-1.0-bazel_0.15.0-autoconfig",
    additional_repos = ubuntu16_04_clang_default_repos(),
    base = "@ubuntu16_04-clang//image",
    bazel_version = "0.15.0",
    env = clang_env() + {
        "BAZEL_LINKOPTS": "-lc++:-lc++abi:-lm",
    },
    keys = ubuntu16_04_clang_default_keys(),
    packages = ubuntu16_04_clang_default_packages(),
    tags = ["manual"],
    test = True,
)

# This target is auto-generated from release/default.tpl and should not be
# modified directly.
# Created on 2018.8.13
# Container: gcr.io/cloud-marketplace/google/clang-ubuntu@sha256:fbf123ca7c7696f53864da4f7d1d9470f9ef4ebfabc4344f44173d1951faee6f
docker_toolchain_autoconfig(
    name = "default-ubuntu16_04-clang-1.0-bazel_0.16.1-autoconfig",
    additional_repos = ubuntu16_04_clang_default_repos(),
    base = "@ubuntu16_04-clang//image",
    bazel_version = "0.16.1",
    env = clang_env(),
    keys = ubuntu16_04_clang_default_keys(),
    packages = ubuntu16_04_clang_default_packages(),
    tags = ["manual"],
    test = True,
)

# This target is auto-generated from release/msan.tpl and should not be
# modified directly.
# Created on 2018.8.13
# Container: gcr.io/cloud-marketplace/google/clang-ubuntu@sha256:fbf123ca7c7696f53864da4f7d1d9470f9ef4ebfabc4344f44173d1951faee6f
docker_toolchain_autoconfig(
    name = "msan-ubuntu16_04-clang-1.0-bazel_0.16.1-autoconfig",
    additional_repos = ubuntu16_04_clang_default_repos(),
    base = "@ubuntu16_04-clang//image",
    bazel_version = "0.16.1",
    env = clang_env() + {
        "BAZEL_LINKOPTS": "-lc++:-lc++abi:-lm",
    },
    keys = ubuntu16_04_clang_default_keys(),
    packages = ubuntu16_04_clang_default_packages(),
    tags = ["manual"],
    test = True,
)

# This target is auto-generated from release/default.tpl and should not be
# modified directly.
# Created on 2018.9.6
# Container: gcr.io/cloud-marketplace/google/clang-ubuntu@sha256:79a24c15949bd5770acac41b444c5c0b7f9723dcbc708c67d87ecf71e32c9126
docker_toolchain_autoconfig(
    name = "default-ubuntu16_04-clang-1.1-bazel_0.16.1-autoconfig",
    additional_repos = ubuntu16_04_clang_default_repos(),
    base = "@ubuntu16_04-clang//image",
    bazel_version = "0.16.1",
    env = clang_env(),
    keys = ubuntu16_04_clang_default_keys(),
    packages = ubuntu16_04_clang_default_packages(),
    tags = ["manual"],
    test = True,
)

# This target is auto-generated from release/msan.tpl and should not be
# modified directly.
# Created on 2018.9.6
# Container: gcr.io/cloud-marketplace/google/clang-ubuntu@sha256:79a24c15949bd5770acac41b444c5c0b7f9723dcbc708c67d87ecf71e32c9126
docker_toolchain_autoconfig(
    name = "msan-ubuntu16_04-clang-1.1-bazel_0.16.1-autoconfig",
    additional_repos = ubuntu16_04_clang_default_repos(),
    base = "@ubuntu16_04-clang//image",
    bazel_version = "0.16.1",
    env = clang_env() + {
        "BAZEL_LINKOPTS": "-lc++:-lc++abi:-lm",
    },
    keys = ubuntu16_04_clang_default_keys(),
    packages = ubuntu16_04_clang_default_packages(),
    tags = ["manual"],
    test = True,
)
