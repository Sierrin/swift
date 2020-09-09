# Swift for TensorFlow

| OS | CI platform | x86_64 | GPU |
|---|:---:|:---:|:---:|
| **macOS** | Google Kokoro | ![Build Status](https://storage.googleapis.com/tensorflow-kokoro-build-badges/macos-swift-tf-release.svg) | - |
| **Ubuntu 16.04** | Swift.org CI | [![Build Status](https://ci-external.swift.org/job/oss-swift-RA-linux-ubuntu-16.04-tensorflow/lastCompletedBuild/badge/icon)](https://ci-external.swift.org/job/oss-swift-RA-linux-ubuntu-16.04-tensorflow) | [![Build Status](https://ci-external.swift.org/job/oss-swift-RA-linux-ubuntu-16.04-tensorflow-gpu/lastCompletedBuild/badge/icon)](https://ci-external.swift.org/job/oss-swift-RA-linux-ubuntu-16.04-tensorflow-gpu) |

| | **Architecture** | **Master** | **Package** |
|---|:---:|:---:|:---:|
| **macOS**        | x86_64 |[![Build Status](https://ci.swift.org/job/oss-swift-incremental-RA-osx/lastCompletedBuild/badge/icon)](https://ci.swift.org/job/oss-swift-incremental-RA-osx)|[![Build Status](https://ci.swift.org/job/oss-swift-package-osx/lastCompletedBuild/badge/icon)](https://ci.swift.org/job/oss-swift-package-osx)|
| **Ubuntu 16.04** | x86_64 | [![Build Status](https://ci.swift.org/job/oss-swift-incremental-RA-linux-ubuntu-16_04/lastCompletedBuild/badge/icon)](https://ci.swift.org/job/oss-swift-incremental-RA-linux-ubuntu-16_04)|[![Build Status](https://ci.swift.org/job/oss-swift-package-linux-ubuntu-16_04/lastCompletedBuild/badge/icon)](https://ci.swift.org/job/oss-swift-package-linux-ubuntu-16_04)|
| **Ubuntu 18.04** | x86_64 | [![Build Status](https://ci.swift.org/job/oss-swift-incremental-RA-linux-ubuntu-18_04/lastCompletedBuild/badge/icon)](https://ci.swift.org/job/oss-swift-incremental-RA-linux-ubuntu-18_04)|[![Build Status](https://ci.swift.org/job/oss-swift-package-linux-ubuntu-18_04/lastCompletedBuild/badge/icon)](https://ci.swift.org/job/oss-swift-package-linux-ubuntu-18_04)|
| **Ubuntu 20.04** | x86_64 | [![Build Status](https://ci.swift.org/job/oss-swift-package-ubuntu-20_04/lastCompletedBuild/badge/icon)](https://ci.swift.org/job/oss-swift-package-ubuntu-20_04)|[![Build Status](https://ci.swift.org/job/oss-swift-package-ubuntu-20_04/lastCompletedBuild/badge/icon)](https://ci.swift.org/job/oss-swift-package-ubuntu-20_04)|
| **CentOS 8** | x86_64 | [![Build Status](https://ci.swift.org/job/oss-swift-package-centos-8/lastCompletedBuild/badge/icon)](https://ci.swift.org/job/oss-swift-package-centos-8)|[![Build Status](https://ci.swift.org/job/oss-swift-package-centos-8/lastCompletedBuild/badge/icon)](https://ci.swift.org/job/oss-swift-package-centos-8)|
| **Amazon Linux 2** | x86_64 | [![Build Status](https://ci.swift.org/job/oss-swift-package-amazon-linux-2/lastCompletedBuild/badge/icon)](https://ci.swift.org/job/oss-swift-package-amazon-linux-2)|[![Build Status](https://ci.swift.org/job/oss-swift-package-amazon-linux-2/lastCompletedBuild/badge/icon)](https://ci.swift.org/job/oss-swift-package-amazon-linux-2)|

**Swift Community-Hosted CI Platforms**

| **OS** | **Architecture** | **Build** |
|---|:---:|:---:|
|**[Ubuntu 16.04 ](https://github.com/apple/swift-community-hosted-continuous-integration/blob/master/nodes/ppc64le_ubuntu_16_04.json)** | PPC64LE |[![Build Status](https://ci-external.swift.org/job/oss-swift-5.1-RA-linux-ubuntu-16.04-ppc64le/lastCompletedBuild/badge/icon)](https://ci-external.swift.org/job/oss-swift-5.1-RA-linux-ubuntu-16.04-ppc64le)|
|**[Ubuntu 18.04](https://github.com/apple/swift-community-hosted-continuous-integration/blob/master/nodes/aarch64_ubuntu_18.04_docker.json)** | AArch64 |[![Build Status](https://ci-external.swift.org/job/oss-swift-RA-ubuntu-18.04-aarch64/lastCompletedBuild/badge/icon)](https://ci-external.swift.org/job/oss-swift-RA-ubuntu-18.04-aarch64)|
|**[Ubuntu 20.04](https://github.com/apple/swift-community-hosted-continuous-integration/blob/master/nodes/aarch64_ubuntu_20.04_docker.json)** | AArch64 |[![Build Status](https://ci-external.swift.org/job/oss-swift-RA-ubuntu-20.04-aarch64/lastCompletedBuild/badge/icon)](https://ci-external.swift.org/job/oss-swift-RA-ubuntu-20.04-aarch64)|
|**[CentOS 8 ](https://github.com/apple/swift-community-hosted-continuous-integration/blob/master/nodes/aarch64_centos_8_docker.json)** | AArch64 |[![Build Status](https://ci-external.swift.org/job/oss-swift-RA-centos8-aarch64/lastCompletedBuild/badge/icon)](https://ci-external.swift.org/job/oss-swift-RA-centos8-aarch64)|
|**[Amazon Linux 2](https://github.com/apple/swift-community-hosted-continuous-integration/blob/master/nodes/aarch64_amazon_linux_2_docker.json)** | AArch64 |[![Build Status](https://ci-external.swift.org/job/oss-swift-RA-amazon-linux-2-aarch64/lastCompletedBuild/badge/icon)](https://ci-external.swift.org/job/oss-swift-RA-amazon-linux-2-aarch64)|
|**[Android](https://github.com/apple/swift-community-hosted-continuous-integration/blob/master/nodes/x86_64_ubuntu_16_04_LTS_android.json)** | ARMv7 |[![Build Status](https://ci-external.swift.org/job/oss-swift-RA-linux-ubuntu-16.04-android/lastCompletedBuild/badge/icon)](https://ci-external.swift.org/job/oss-swift-RA-linux-ubuntu-16.04-android)|
|**[Android](https://github.com/apple/swift-community-hosted-continuous-integration/blob/master/nodes/x86_64_ubuntu_16_04_LTS_android.json)** | AArch64 |[![Build Status](https://ci-external.swift.org/job/oss-swift-RA-linux-ubuntu-16.04-android-arm64/lastCompletedBuild/badge/icon)](https://ci-external.swift.org/job/oss-swift-RA-linux-ubuntu-16.04-android-arm64)|
|**[Windows 2019 (VS 2017)](https://github.com/apple/swift-community-hosted-continuous-integration/blob/master/nodes/x86_64_windows_2019.json)** | x86_64 | [![Build Status](https://ci-external.swift.org/job/oss-swift-windows-x86_64/lastCompletedBuild/badge/icon)](https://ci-external.swift.org/job/oss-swift-windows-x86_64)|
|**[Windows 2019 (VS 2019)](https://github.com/apple/swift-community-hosted-continuous-integration/blob/master/nodes/x86_64_windows_2019_VS2019.json)** | x86_64 | [![Build Status](https://ci-external.swift.org/job/oss-swift-windows-x86_64-vs2019/lastCompletedBuild/badge/icon)](https://ci-external.swift.org/job/oss-swift-windows-x86_64-vs2019)|

**Swift TensorFlow Community-Hosted CI Platforms**

| **OS** | **Architecture** | **Build** |
|---|:---:|:---:|
|**[Ubuntu 16.04](https://github.com/apple/swift-community-hosted-continuous-integration/blob/master/nodes/x86_64_ubuntu_16_04_tensorflow.json)** | x86_64 |[![Build Status](https://ci-external.swift.org/job/oss-swift-RA-linux-ubuntu-16.04-tensorflow/lastCompletedBuild/badge/icon)](https://ci-external.swift.org/job/oss-swift-RA-linux-ubuntu-16.04-tensorflow)|
|**[macOS 10.13](https://github.com/apple/swift-community-hosted-continuous-integration/blob/master/nodes/x86_64_macos_high_sierra_tensorflow.json)** | x86_64 |[![Build Status](https://ci-external.swift.org/job/oss-swift-RA-macOS-tensorflow/lastCompletedBuild/badge/icon)](https://ci-external.swift.org/job/oss-swift-RA-macOS-tensorflow)|
|**[Ubuntu 16.04 (GPU)](https://github.com/apple/swift-community-hosted-continuous-integration/blob/master/nodes/x86_64_ubuntu_16_04_tensorflow_gpu.json)** | x86_64 |[![Build Status](https://ci-external.swift.org/job/oss-swift-RA-linux-ubuntu-16.04-tensorflow-gpu/lastCompletedBuild/badge/icon)](https://ci-external.swift.org/job/oss-swift-RA-linux-ubuntu-16.04-tensorflow-gpu)|

<!-- SWIFT_ENABLE_TENSORFLOW -->

Swift for TensorFlow is a new programming language for TensorFlow. It is a copy of the compiler for the [Swift Programming Language](https://swift.org) that adds first-class compiler and language support for machine learning.

This repository covers the compiler and standard libraries. Please visit the [documentation repository](https://github.com/tensorflow/swift) for more information about the project, including a project overview, technical details, and guidelines for contributing. To use Swift for TensorFlow out of the box, follow the [installation instructions](https://github.com/tensorflow/swift/blob/master/Installation.md). To build from source, follow the instructions below.
<!-- SWIFT_ENABLE_TENSORFLOW END -->

## Welcome to Swift

Swift is a high-performance system programming language.  It has a clean
and modern syntax, offers seamless access to existing C and Objective-C code
and frameworks, and is memory safe by default.

Although inspired by Objective-C and many other languages, Swift is not itself a
C-derived language. As a complete and independent language, Swift packages core
features like flow control, data structures, and functions, with high-level
constructs like objects, protocols, closures, and generics. Swift embraces
modules, eliminating the need for headers and the code duplication they entail.

To learn more about the programming language, visit [swift.org](https://swift.org/documentation/).

- [Contributing to Swift](#contributing-to-swift)
- [Getting Started](#getting-started)
  - [Swift Toolchains](#swift-toolchains)
  - [Build Failures](#build-failures)
- [Learning More](#learning-more)

## Contributing to Swift

Contributions to Swift are welcomed and encouraged! Please see the
[Contributing to Swift guide](https://swift.org/contributing/).

To be a truly great community, [Swift.org](https://swift.org/) needs to welcome
developers from all walks of life, with different backgrounds, and with a wide
range of experience. A diverse and friendly community will have more great
ideas, more unique perspectives, and produce more great code. We will work
diligently to make the Swift community welcoming to everyone.

To give clarity of what is expected of our members, Swift has adopted the
code of conduct defined by the Contributor Covenant. This document is used
across many open source communities, and we think it articulates our values
well. For more, see the [Code of Conduct](https://swift.org/community/#code-of-conduct).

## Getting Started

If you are interested in:
- Contributing fixes and features to the compiler: See our
  [How to Submit Your First Pull Request guide](/docs/HowToGuides/FirstPullRequest.md).
- Building the compiler as a one-off: See our [Getting Started guide][].
- Building a toolchain as a one-off: Follow the [Getting Started guide][]
  up until the "Building the project" section. After that, follow the
  instructions in the [Swift Toolchains](#swift-toolchains) section below.

[Getting Started guide]: /docs/HowToGuides/GettingStarted.md

### Swift For TensorFlow Toolchains

#### Building

Swift for TensorFlow toolchains are created using the script
[build-toolchain-tensorflow](https://github.com/apple/swift/blob/tensorflow/utils/build-toolchain-tensorflow).
This script is used by swift.org's CI to produce snapshots and can allow for one to
locally reproduce such builds for development or distribution purposes. A typical 
invocation looks like the following:

```
  $ ./swift/utils/build-toolchain-tensorflow $BUNDLE_PREFIX
```

where ``$BUNDLE_PREFIX`` is a string that will be prepended to the build
date to give the bundle identifier of the toolchain's ``Info.plist``. For
instance, if ``$BUNDLE_PREFIX`` was ``com.example``, the toolchain
produced will have the bundle identifier ``com.example.YYYYMMDD``. It
will be created in the directory you run the script with a filename
 of the form: ``swift-tensorflow-LOCAL-YYYY-MM-DD-a-osx.tar.gz``.

Beyond building the toolchain, ``build-toolchain-tensorflow`` also supports the
following (non-exhaustive) set of useful options:

- ``--dry-run``: Perform a dry run build. This is off by default.
- ``--test``: Test the toolchain after it has been compiled. This is off by default.
- ``--pkg`` (macOS only): Build a toolchain installer package (`.pkg`). This is off by default.

More options may be added over time. Please pass ``--help`` to
``build-toolchain-tensorflow`` to see the full set of options.

#### Installing into Xcode

On macOS if one wants to install such a toolchain into Xcode:

1. Untar and copy the toolchain to one of `/Library/Developer/Toolchains/` or
   `~/Library/Developer/Toolchains/`. E.x.:

```
  $ sudo tar -xzf swift-LOCAL-YYYY-MM-DD-a-osx.tar.gz -C /
  $ tar -xzf swift-LOCAL-YYYY-MM-DD-a-osx.tar.gz -C ~/
```

The script also generates an archive containing debug symbols which
can be installed over the main archive allowing symbolication of any
compiler crashes.

```
  $ sudo tar -xzf swift-LOCAL-YYYY-MM-DD-a-osx-symbols.tar.gz -C /
  $ tar -xzf swift-LOCAL-YYYY-MM-DD-a-osx-symbols.tar.gz -C ~/
```

2. Specify the local toolchain for Xcode's use via `Xcode->Toolchains`.

### Build Failures

Try the suggestions in
[Troubleshooting build issues](/docs/HowToGuides/GettingStarted.md#troubleshooting-build-issues).

Make sure you are using the
[correct release](/docs/HowToGuides/GettingStared.md#installing-dependencies)
of Xcode.

If you have changed Xcode versions but still encounter errors that appear to
be related to the Xcode version, try passing `--clean` to `build-script`.

When a new version of Xcode is released, you can update your build without
recompiling the entire project by passing the `--reconfigure` option.

## Learning More

Be sure to look at the [documentation index](/docs/README.md) for a bird's eye
view of the available documentation. In particular, the documents titled
[Debugging the Swift Compiler](docs/DebuggingTheCompiler.md) and
[Continuous Integration for Swift](docs/ContinuousIntegration.md) are very
helpful to understand before submitting your first PR.

### Building Documentation

To read the compiler documentation, start by installing the
[Sphinx](http://sphinx-doc.org) documentation generator tool by running the
command:

    easy_install -U "Sphinx < 2.0"

Once complete, you can build the Swift documentation by changing directory into
[docs](https://github.com/apple/swift/tree/master/docs) and typing `make`. This
compiles the `.rst` files in the [docs](https://github.com/apple/swift/tree/master/docs)
directory into HTML in the `docs/_build/html` directory.

Many of the docs are out of date, but you can see some historical design
documents in the `docs` directory.

Another source of documentation is the standard library itself, located in
`stdlib`. Much of the language is actually implemented in the library
(including `Int`), and the standard library gives some examples of what can be
expressed today.

## Build Dependencies

### CMake
[CMake](https://cmake.org) is the core infrastructure used to configure builds of
Swift and its companion projects; at least version 3.16.5 is required.

On macOS, you can download the [CMake Binary Distribution](https://cmake.org/download),
bundled as an application, copy it to `/Applications`, and add the embedded
command line tools to your `PATH`:

    export PATH=/Applications/CMake.app/Contents/bin:$PATH

On Linux, if you have not already installed Swift's [development
dependencies](#linux), you can download and install the CMake
package separately using the following command:

    sudo apt-get install cmake


### Ninja
[Ninja](https://ninja-build.org) is the current recommended build system
for building Swift and is the default configuration generated by CMake. [Pre-built
packages](https://github.com/ninja-build/ninja/wiki/Pre-built-Ninja-packages)
are available for macOS and Linux distributions. You can also clone Ninja
next to the other projects and it will be bootstrapped automatically:

**Via HTTPS**

    git clone https://github.com/ninja-build/ninja.git && cd ninja
    git checkout release
    cat README

**Via SSH**

    git clone git@github.com:ninja-build/ninja.git && cd ninja
    git checkout release
    cat README

### Bazel
[Bazel](https://bazel.build) is the build tool used to build TensorFlow. Installing Bazel is necessary for building Swift with TensorFlow support.

The Bazel website has detailed installation instructions for
[macOS](https://docs.bazel.build/versions/master/install-os-x.html) and
[Ubuntu](https://docs.bazel.build/versions/master/install-ubuntu.html).
When picking the version to download in step 2, select version 2.0.0 which can be found in the release notes [here (v2.0.0)](https://github.com/bazelbuild/bazel/releases/tag/2.0.0).
