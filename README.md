# ReVanced
[![CI](https://github.com/AbakNacchan/revanced-magisk-module/actions/workflows/ci.yml/badge.svg?event=schedule)](https://github.com/AbakNacchan/revanced-magisk-module/actions/workflows/ci.yml)

## Extensive ReVanced Builder

※ Get the [latest CI release](https://github.com/AbakNacchan/revanced-magisk-module/releases) ※


#### ReVanced eXtended
If you are interested on using `ReVanced eXtended` instead, you always can go and start [here](https://github.com/AbakNacchan/revanced-extended).


<details><summary><big>Features</big></summary>
<ul>
 <li>Support all present and future ReVanced apps</li>
 <li>Can build Magisk modules and non-root APKs</li>
 <li>Updated periodically with the latest versions of apps and patches</li>
 <li>Optimize APKs and modules for size</li>
 <li>Modules</li>
    <ul>
     <li>Provide support for ReVanced apps, both current and upcoming</li>
     <li>Enable the creation of Magisk modules and non-root APKs</li>
     <li>Offer regular updates with the newest versions of apps and patches</li>
     <li>Reduce the size of APKs and modules for optimization</li>
     <li>Compatible with Magisk and KernelSU</li>
    </ul>
</ul>
Be aware that the <a href="../../actions/workflows/ci.yml">CI workflow</a> automatically builds the modules and APKs every day using GitHub Actions, as long as there is a change in ReVanced patches. You might want to turn it off.
</details>

## To include/exclude patches or to patch other apps
[**See the list of patches**](https://j-hc.github.io/rvmm-config-gen/)

 * Star the repo
 * Use the repo as a [template](https://github.com/AbakNacchan/revanced-magisk-module/fork)
 * Customize [`config.toml`](./config.toml) using [rvmm-config-gen](https://j-hc.github.io/rvmm-config-gen/)
 * Run the build [workflow](../../actions/workflows/build.yml)
 * Grab your modules and APKs from [releases](../../releases)

Also see [`CONFIG.md`](./CONFIG.md).

## Building Locally
### On Termux
```console
bash <(curl -sSf https://raw.githubusercontent.com/AbakNacchan/revanced-magisk-module/main/build-termux.sh)
```

### On Desktop
```console
$ git clone https://github.com/AbakNacchan/revanced-magisk-module
$ cd revanced-magisk-module
$ ./build.sh
```
