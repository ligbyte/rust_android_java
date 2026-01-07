# rust_android_java

  Rust 在Android Java中的应用示例 [掘金教程1](https://juejin.cn/post/7388050022782681140)  [掘金教程2](https://juejin.cn/post/7170696817682694152?from=search-suggest)


[AndroidRustDemo](https://github.com/angcyo/AndroidRustDemo)
[AndroidRustDemo](https://github.com/Mrack/AndroidRustDemo#)
[AndroidRustDemo](https://github.com/BruceXuheng/AndroidRustDemo)
[android-rust-jni](https://github.com/hushenghao/android-rust-jni#)
[rust-android-demo](https://github.com/angcyo/rust-android-demo#)
[greeting-demo](https://github.com/alfinsyahruddin/greeting-demo#)
[jni_demo](https://github.com/jiker-burce/jni_demo#)


cargo install cargo-ndk

cargo ndk -t armeabi-v7a -t arm64-v8a -o ../src/main/jniLibs build  --release


rustup target add armv7-linux-androideabi   # for arm
rustup target add aarch64-linux-android     # for arm64
rustup target add i686-linux-android        # for x86
rustup target add x86_64-linux-android      # for x86_64

rustup target add x86_64-unknown-linux-gnu  # for linux-x86-64
rustup target add x86_64-apple-darwin       # for darwin x86_64 (if you have an Intel MacOS)
rustup target add aarch64-apple-darwin      # for darwin arm64 (if you have a M1 MacOS)
rustup target add x86_64-pc-windows-gnu     # for win32-x86-64-gnu
rustup target add x86_64-pc-windows-msvc    # for win32-x86-64-msvc
...

