Run the devserver with `bazel run dev`.

Running `bazel build prod` leads to

```
- Building...

app:build:production: ✘ [ERROR] File '../../../../../../../../execroot/_main/bazel-out/darwin_arm64-fastbuild/bin/src/main.ts' is missing from the TypeScript compilation. [plugin angular-compiler]

  Ensure the file is part of the TypeScript program via the 'files' or 'include' property.

```
