# pcap-reader
Simple wrapper around [pcap4j](https://github.com/kaitoy/pcap4j)'s `.pcap` and `nif` reader (`PcapHandle`). The purpose is to reduce the amount of necessary boilerplate code when reading from a `.pcap` file.

## Include as dependency in your project
Use [JitPack](https://jitpack.io/) to include `pcap-reader` in your project. For example, if using Gradle:
1. Add the JitPack repository to your `build.gradle`:
```
repositories {
    ... // other repos
    maven { url 'https://jitpack.io' }
}
```
2. Add the dependency to your `build.gradle` (replacing `2554df508ef8185b9cca04d9ee681e7e52ef2eeb` with the hash of the most recent commit or a release tag):
```
...
dependencies {
    implementation 'com.github.jvmk:pcap-reader:2554df508ef8185b9cca04d9ee681e7e52ef2eeb'
}
...
```
