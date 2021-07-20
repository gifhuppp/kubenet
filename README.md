# kubenet
travis_fold:start:worker_info
[0K[33;1mWorker information[0m
hostname: a139a0e1-d68c-4add-aa13-109f8c423d0a@1.worker-org-f578479c5-6c4jm.macstadium-prod-1
version: v6.2.0 https://github.com/travis-ci/worker/tree/5e5476e01646095f48eec13196fdb3faf8f5cbf7
instance: adb9d146-66de-4ee7-bba4-f4ddb5877e09 travis-ci-macos10.13-xcode9.4.1-19-1576204381 (via amqp)
startup: 1m2.109805792s
travis_fold:end:worker_info
[0Ktravis_time:start:014baba4
[0Ktravis_time:end:014baba4:start=1620446981391638000,finish=1620446981928709000,duration=537071000,event=no_world_writable_dirs
[0Ktravis_time:start:06cfd6ec
[0Ktravis_time:end:06cfd6ec:start=1620446981937284000,finish=1620446981946218000,duration=8934000,event=setup_filter
[0Ktravis_time:start:14086f47
[0Ktravis_time:end:14086f47:start=1620446981959219000,finish=1620446981965701000,duration=6482000,event=check_unsupported
[0Ktravis_time:start:1798c9f4
[0Ktravis_fold:start:system_info
[0K[33;1mBuild system information[0m

Build language: objective-c

Build id: 770046291

Job id: 770046292

Runtime kernel version: 17.7.0

travis-build version: 091d532a

[34m[1mBuild image provisioning date and time[0m

Fri Dec 13 04:54:58 GMT 2019

[34m[1mOperating System Details[0m

ProductName:	Mac OS X

ProductVersion:	10.13.6

BuildVersion:	17G65

[34m[1mGit version[0m

git version 2.24.1

[34m[1mbash version[0m

GNU bash, version 3.2.57(1)-release (x86_64-apple-darwin17)

Copyright (C) 2007 Free Software Foundation, Inc.

[34m[1mGCC version[0m

Apple LLVM version 9.1.0 (clang-902.0.39.2)

Target: x86_64-apple-darwin17.7.0

Thread model: posix

InstalledDir: /Applications/Xcode-9.4.1.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin

[34m[1mLLVM version[0m

Apple LLVM version 9.1.0 (clang-902.0.39.2)

Target: x86_64-apple-darwin17.7.0

Thread model: posix

InstalledDir: /Applications/Xcode-9.4.1.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin

[34m[1mPre-installed Ruby versions[0m

ruby-2.6.3

[34m[1mPre-installed Node.js versions[0m

v10.17.0

v12.13.0

v12.13.1

v13.0.1

v4.9.1

v6.17.1

v8.16.2

[34m[1mmvn -version[0m

Apache Maven 3.6.3 (cecedd343002696d0abb50b32b541b8a6ba2883f)

Maven home: /usr/local/Cellar/maven/3.6.3/libexec

Java version: 13.0.1, vendor: Oracle Corporation, runtime: /Library/Java/JavaVirtualMachines/openjdk-13.0.1.jdk/Contents/Home

Default locale: en_US, platform encoding: UTF-8

OS name: "mac os x", version: "10.13.6", arch: "x86_64", family: "mac"

travis_fold:end:system_info
[0K

travis_time:end:1798c9f4:start=1620446981974479000,finish=1620446981989989000,duration=15510000,event=show_system_info
[0Ktravis_time:start:00d876b0
[0Ktravis_time:end:00d876b0:start=1620446981997519000,finish=1620446982006704000,duration=9185000,event=rm_riak_source
[0Ktravis_time:start:062114f0
[0Ktravis_time:end:062114f0:start=1620446982013435000,finish=1620446982019541000,duration=6106000,event=fix_rwky_redis
[0Ktravis_time:start:0aa8aac0
[0Ktravis_time:end:0aa8aac0:start=1620446982026354000,finish=1620446982777156000,duration=750802000,event=wait_for_network
[0Ktravis_time:start:1ddfe16c
[0Ktravis_time:end:1ddfe16c:start=1620446982786448000,finish=1620446982793529000,duration=7081000,event=update_apt_keys
[0Ktravis_time:start:03a10883
[0Ktravis_time:end:03a10883:start=1620446982802384000,finish=1620446982810026000,duration=7642000,event=fix_hhvm_source
[0Ktravis_time:start:01e65090
[0Ktravis_time:end:01e65090:start=1620446982818906000,finish=1620446982825750000,duration=6844000,event=update_mongo_arch
[0Ktravis_time:start:0cbccda0
[0Ktravis_time:end:0cbccda0:start=1620446982834687000,finish=1620446982844196000,duration=9509000,event=fix_sudo_enabled_trusty
[0Ktravis_time:start:13f4fb0e
[0Ktravis_time:end:13f4fb0e:start=1620446982853449000,finish=1620446982859878000,duration=6429000,event=update_glibc
[0Ktravis_time:start:00e2569c
[0Ktravis_time:end:00e2569c:start=1620446982868903000,finish=1620446982911821000,duration=42918000,event=clean_up_path
[0Ktravis_time:start:2da362bd
[0Ktravis_time:end:2da362bd:start=1620446982921107000,finish=1620446982963299000,duration=42192000,event=fix_resolv_conf
[0Ktravis_time:start:019642bf
[0Ktravis_time:end:019642bf:start=1620446982972548000,finish=1620446983017080000,duration=44532000,event=fix_etc_hosts
[0Ktravis_time:start:1a358502
[0Ktravis_time:end:1a358502:start=1620446983026018000,finish=1620446983031814000,duration=5796000,event=fix_mvn_settings_xml
[0Ktravis_time:start:03458320
[0Ktravis_time:end:03458320:start=1620446983040872000,finish=1620446983085468000,duration=44596000,event=no_ipv6_localhost
[0Ktravis_time:start:319c8c82
[0Ktravis_time:end:319c8c82:start=1620446983094275000,finish=1620446983100335000,duration=6060000,event=fix_etc_mavenrc
[0Ktravis_time:start:0dcc4818
[0Ktravis_time:end:0dcc4818:start=1620446983109186000,finish=1620446983659200000,duration=550014000,event=fix_wwdr_certificate
[0Ktravis_time:start:010ea843
[0Ktravis_time:end:010ea843:start=1620446983668173000,finish=1620446983848278000,duration=180105000,event=put_localhost_first
[0Ktravis_time:start:0e817495
[0Ktravis_time:end:0e817495:start=1620446983857644000,finish=1620446983864794000,duration=7150000,event=home_paths
[0Ktravis_time:start:0f472452
[0Ktravis_time:end:0f472452:start=1620446983873749000,finish=1620446983887984000,duration=14235000,event=disable_initramfs
[0Ktravis_time:start:00ab0975
[0Ktravis_time:end:00ab0975:start=1620446983896298000,finish=1620446983918652000,duration=22354000,event=disable_ssh_roaming
[0Ktravis_time:start:051ec268
[0Ktravis_time:end:051ec268:start=1620446983927206000,finish=1620446983933735000,duration=6529000,event=debug_tools
[0Ktravis_time:start:08bbcb9d
[0K

travis_time:end:08bbcb9d:start=1620446983941821000,finish=1620446987077279000,duration=3135458000,event=uninstall_oclint
[0Ktravis_time:start:050b15c2
[0Ktravis_time:end:050b15c2:start=1620446987089173000,finish=1620446987978163000,duration=888990000,event=rvm_use
[0Ktravis_time:start:01e7e9ed
[0Ktravis_time:end:01e7e9ed:start=1620446987988349000,finish=1620446988035074000,duration=46725000,event=rm_etc_boto_cfg
[0Ktravis_time:start:061f7ef2
[0Ktravis_time:end:061f7ef2:start=1620446988044890000,finish=1620446988051174000,duration=6284000,event=rm_oraclejdk8_symlink
[0Ktravis_time:start:014f5afd
[0Ktravis_time:end:014f5afd:start=1620446988061919000,finish=1620446988073950000,duration=12031000,event=enable_i386
[0Ktravis_time:start:10d55a77
[0Ktravis_time:end:10d55a77:start=1620446988084353000,finish=1620446988095372000,duration=11019000,event=update_rubygems
[0Ktravis_time:start:18297955
[0Ktravis_time:end:18297955:start=1620446988105276000,finish=1620446988120860000,duration=15584000,event=ensure_path_components
[0Ktravis_time:start:23fa6516
[0Ktravis_time:end:23fa6516:start=1620446988131618000,finish=1620446988138030000,duration=6412000,event=redefine_curl
[0Ktravis_time:start:059ac4f5
[0Ktravis_time:end:059ac4f5:start=1620446988149263000,finish=1620446988219776000,duration=70513000,event=nonblock_pipe
[0Ktravis_time:start:0c6679e7
[0Ktravis_time:end:0c6679e7:start=1620446988230015000,finish=1620446988238745000,duration=8730000,event=apt_get_update
[0Ktravis_time:start:1196d2d0
[0Ktravis_time:end:1196d2d0:start=1620446988248291000,finish=1620446988255455000,duration=7164000,event=deprecate_xcode_64
[0Ktravis_time:start:182f133c
[0Ktravis_time:end:182f133c:start=1620446988265301000,finish=1620446988302938000,duration=37637000,event=update_heroku
[0Ktravis_time:start:01b92b6a
[0Ktravis_time:end:01b92b6a:start=1620446988316356000,finish=1620446988327764000,duration=11408000,event=shell_session_update
[0Ktravis_time:start:027317d4
[0Ktravis_time:end:027317d4:start=1620446988340585000,finish=1620446988348156000,duration=7571000,event=maven_central_mirror
[0Ktravis_time:start:0a7ac197
[0Ktravis_time:end:0a7ac197:start=1620446988359242000,finish=1620446988367309000,duration=8067000,event=maven_https
[0Ktravis_time:start:0ae19e54
[0Ktravis_time:end:0ae19e54:start=1620446988378523000,finish=1620446988389545000,duration=11022000,event=fix_ps4
[0Ktravis_time:start:16e39e10
[0K

travis_fold:start:git.checkout
[0Ktravis_time:start:0090295b
[0K$ git clone --depth=50 https://github.com/atom/fuzzy-finder.git atom/fuzzy-finder

Cloning into 'atom/fuzzy-finder'...

travis_time:end:0090295b:start=1620446988409702000,finish=1620446988897236000,duration=487534000,event=checkout
[0K$ cd atom/fuzzy-finder

travis_time:start:0270a9e6
[0K$ git fetch origin +refs/pull/434/merge:

From https://github.com/atom/fuzzy-finder

 * branch            refs/pull/434/merge -> FETCH_HEAD

travis_time:end:0270a9e6:start=1620446988942392000,finish=1620446989296192000,duration=353800000,event=checkout
[0K$ git checkout -qf FETCH_HEAD

travis_fold:end:git.checkout
[0K

travis_time:end:0270a9e6:start=1620446988942392000,finish=1620446989324813000,duration=382421000,event=checkout
[0Ktravis_time:start:02892336
[0K

[33;1mSetting environment variables from repository settings[0m

$ export GITHUB_TOKEN=[secure]



travis_time:end:02892336:start=1620446989334467000,finish=1620446989361778000,duration=27311000,event=env
[0K[33;1mDisabling Homebrew auto update. If your Homebrew package requires Homebrew DB be up to date, please run `brew update` explicitly.[0m

$ export HOMEBREW_NO_AUTO_UPDATE=1

travis_fold:start:rvm
[0Ktravis_time:start:2f05c74f
[0K$ rvm use default

Using /Users/travis/.rvm/gems/ruby-2.6.3

travis_time:end:2f05c74f:start=1620446989381428000,finish=1620446991106749000,duration=1725321000,event=setup
[0Ktravis_fold:end:rvm
[0K

$ ruby --version

ruby 2.6.3p62 (2019-04-16 revision 67580) [x86_64-darwin17]

$ rvm --version

rvm 1.29.8 (latest) by Michal Papis, Piotr Kuczynski, Wayne E. Seguin [https://rvm.io]

$ bundle --version

Bundler version 2.0.2

travis_fold:start:announce
[0K$ xcodebuild -version -sdk

iPhoneOS11.4.sdk - iOS 11.4 (iphoneos11.4)

SDKVersion: 11.4

Path: /Applications/Xcode-9.4.1.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS11.4.sdk

PlatformVersion: 11.4

PlatformPath: /Applications/Xcode-9.4.1.app/Contents/Developer/Platforms/iPhoneOS.platform

BuildID: F6E11FE6-5596-11E8-9BDA-5AB96C5CAEA5

ProductBuildVersion: 15F79

ProductCopyright: 1983-2018 Apple Inc.

ProductName: iPhone OS

ProductVersion: 11.4



iPhoneSimulator11.4.sdk - Simulator - iOS 11.4 (iphonesimulator11.4)

SDKVersion: 11.4

Path: /Applications/Xcode-9.4.1.app/Contents/Developer/Platforms/iPhoneSimulator.platform/Developer/SDKs/iPhoneSimulator11.4.sdk

PlatformVersion: 11.4

PlatformPath: /Applications/Xcode-9.4.1.app/Contents/Developer/Platforms/iPhoneSimulator.platform

BuildID: F6E11FE6-5596-11E8-9BDA-5AB96C5CAEA5

ProductBuildVersion: 15F79

ProductCopyright: 1983-2018 Apple Inc.

ProductName: iPhone OS

ProductVersion: 11.4



MacOSX10.13.sdk - macOS 10.13 (macosx10.13)

SDKVersion: 10.13

Path: /Applications/Xcode-9.4.1.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX10.13.sdk

PlatformVersion: 1.1

PlatformPath: /Applications/Xcode-9.4.1.app/Contents/Developer/Platforms/MacOSX.platform

ProductBuildVersion: 17E189

ProductCopyright: 1983-2018 Apple Inc.

ProductName: Mac OS X

ProductUserVisibleVersion: 10.13.4

ProductVersion: 10.13.4



AppleTVOS11.4.sdk - tvOS 11.4 (appletvos11.4)

SDKVersion: 11.4

Path: /Applications/Xcode-9.4.1.app/Contents/Developer/Platforms/AppleTVOS.platform/Developer/SDKs/AppleTVOS11.4.sdk

PlatformVersion: 11.4

PlatformPath: /Applications/Xcode-9.4.1.app/Contents/Developer/Platforms/AppleTVOS.platform

BuildID: 2A4D8C64-54C2-11E8-9ADF-18993D72DF6D

ProductBuildVersion: 15L576

ProductCopyright: 1983-2018 Apple Inc.

ProductName: Apple TVOS

ProductVersion: 11.4



AppleTVSimulator11.4.sdk - Simulator - tvOS 11.4 (appletvsimulator11.4)

SDKVersion: 11.4

Path: /Applications/Xcode-9.4.1.app/Contents/Developer/Platforms/AppleTVSimulator.platform/Developer/SDKs/AppleTVSimulator11.4.sdk

PlatformVersion: 11.4

PlatformPath: /Applications/Xcode-9.4.1.app/Contents/Developer/Platforms/AppleTVSimulator.platform

BuildID: 2A4D8C64-54C2-11E8-9ADF-18993D72DF6D

ProductBuildVersion: 15L576

ProductCopyright: 1983-2018 Apple Inc.

ProductName: Apple TVOS

ProductVersion: 11.4



WatchOS4.3.sdk - watchOS 4.3 (watchos4.3)

SDKVersion: 4.3

Path: /Applications/Xcode-9.4.1.app/Contents/Developer/Platforms/WatchOS.platform/Developer/SDKs/WatchOS4.3.sdk

PlatformVersion: 4.3

PlatformPath: /Applications/Xcode-9.4.1.app/Contents/Developer/Platforms/WatchOS.platform

BuildID: 4AF39DC2-2782-11E8-A671-639E35235AA8

ProductBuildVersion: 15T212

ProductCopyright: 1983-2018 Apple Inc.

ProductName: Watch OS

ProductVersion: 4.3



WatchSimulator4.3.sdk - Simulator - watchOS 4.3 (watchsimulator4.3)

SDKVersion: 4.3

Path: /Applications/Xcode-9.4.1.app/Contents/Developer/Platforms/WatchSimulator.platform/Developer/SDKs/WatchSimulator4.3.sdk

PlatformVersion: 4.3

PlatformPath: /Applications/Xcode-9.4.1.app/Contents/Developer/Platforms/WatchSimulator.platform

BuildID: 4AF39DC2-2782-11E8-A671-639E35235AA8

ProductBuildVersion: 15T212

ProductCopyright: 1983-2018 Apple Inc.

ProductName: Watch OS

ProductVersion: 4.3



Xcode 9.4.1

Build version 9F2000

$ xcrun simctl list

== Device Types ==

iPhone 4s (com.apple.CoreSimulator.SimDeviceType.iPhone-4s)

iPhone 5 (com.apple.CoreSimulator.SimDeviceType.iPhone-5)

iPhone 5s (com.apple.CoreSimulator.SimDeviceType.iPhone-5s)

iPhone 6 (com.apple.CoreSimulator.SimDeviceType.iPhone-6)

iPhone 6 Plus (com.apple.CoreSimulator.SimDeviceType.iPhone-6-Plus)

iPhone 6s (com.apple.CoreSimulator.SimDeviceType.iPhone-6s)

iPhone 6s Plus (com.apple.CoreSimulator.SimDeviceType.iPhone-6s-Plus)

iPhone 7 (com.apple.CoreSimulator.SimDeviceType.iPhone-7)

iPhone 7 Plus (com.apple.CoreSimulator.SimDeviceType.iPhone-7-Plus)

iPhone 8 (com.apple.CoreSimulator.SimDeviceType.iPhone-8)

iPhone 8 Plus (com.apple.CoreSimulator.SimDeviceType.iPhone-8-Plus)

iPhone SE (com.apple.CoreSimulator.SimDeviceType.iPhone-SE)

iPhone X (com.apple.CoreSimulator.SimDeviceType.iPhone-X)

iPad 2 (com.apple.CoreSimulator.SimDeviceType.iPad-2)

iPad Retina (com.apple.CoreSimulator.SimDeviceType.iPad-Retina)

iPad Air (com.apple.CoreSimulator.SimDeviceType.iPad-Air)

iPad Air 2 (com.apple.CoreSimulator.SimDeviceType.iPad-Air-2)

iPad (5th generation) (com.apple.CoreSimulator.SimDeviceType.iPad--5th-generation-)

iPad Pro (9.7-inch) (com.apple.CoreSimulator.SimDeviceType.iPad-Pro--9-7-inch-)

iPad Pro (12.9-inch) (com.apple.CoreSimulator.SimDeviceType.iPad-Pro)

iPad Pro (12.9-inch) (2nd generation) (com.apple.CoreSimulator.SimDeviceType.iPad-Pro--12-9-inch---2nd-generation-)

iPad Pro (10.5-inch) (com.apple.CoreSimulator.SimDeviceType.iPad-Pro--10-5-inch-)

iPad (6th generation) (com.apple.CoreSimulator.SimDeviceType.iPad--6th-generation-)

Apple TV (com.apple.CoreSimulator.SimDeviceType.Apple-TV-1080p)

Apple TV 4K (com.apple.CoreSimulator.SimDeviceType.Apple-TV-4K-4K)

Apple TV 4K (at 1080p) (com.apple.CoreSimulator.SimDeviceType.Apple-TV-4K-1080p)

Apple Watch - 38mm (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-38mm)

Apple Watch - 42mm (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-42mm)

Apple Watch Series 2 - 38mm (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-2-38mm)

Apple Watch Series 2 - 42mm (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-2-42mm)

Apple Watch Series 3 - 38mm (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-3-38mm)

Apple Watch Series 3 - 42mm (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-3-42mm)

== Runtimes ==

iOS 8.1 (8.1 - 12B411) - com.apple.CoreSimulator.SimRuntime.iOS-8-1

iOS 8.2 (8.2 - 12D508) - com.apple.CoreSimulator.SimRuntime.iOS-8-2

iOS 8.3 (8.3 - 12F70) - com.apple.CoreSimulator.SimRuntime.iOS-8-3

iOS 8.4 (8.4 - 12H141) - com.apple.CoreSimulator.SimRuntime.iOS-8-4

iOS 9.0 (9.0 - 13A344) - com.apple.CoreSimulator.SimRuntime.iOS-9-0

iOS 9.1 (9.1 - 13B143) - com.apple.CoreSimulator.SimRuntime.iOS-9-1

iOS 9.2 (9.2 - 13C75) - com.apple.CoreSimulator.SimRuntime.iOS-9-2

iOS 9.3 (9.3 - 13E233) - com.apple.CoreSimulator.SimRuntime.iOS-9-3

iOS 10.0 (10.0 - 14A345) - com.apple.CoreSimulator.SimRuntime.iOS-10-0

iOS 10.1 (10.1 - 14B72) - com.apple.CoreSimulator.SimRuntime.iOS-10-1

iOS 10.2 (10.2 - 14C89) - com.apple.CoreSimulator.SimRuntime.iOS-10-2

iOS 10.3 (10.3.1 - 14E8301) - com.apple.CoreSimulator.SimRuntime.iOS-10-3

iOS 11.0 (11.0.1 - 15A8401) - com.apple.CoreSimulator.SimRuntime.iOS-11-0

iOS 11.1 (11.1 - 15B87) - com.apple.CoreSimulator.SimRuntime.iOS-11-1

iOS 11.2 (11.2 - 15C107) - com.apple.CoreSimulator.SimRuntime.iOS-11-2

iOS 11.3 (11.3 - 15E217) - com.apple.CoreSimulator.SimRuntime.iOS-11-3

iOS 11.4 (11.4 - 15F79) - com.apple.CoreSimulator.SimRuntime.iOS-11-4

tvOS 9.0 (9.0 - 13T395) - com.apple.CoreSimulator.SimRuntime.tvOS-9-0

tvOS 9.1 (9.1 - 13U85) - com.apple.CoreSimulator.SimRuntime.tvOS-9-1

tvOS 9.2 (9.2 - 13Y234) - com.apple.CoreSimulator.SimRuntime.tvOS-9-2

tvOS 10.0 (10.0 - 14T328) - com.apple.CoreSimulator.SimRuntime.tvOS-10-0

tvOS 10.1 (10.1 - 14U591) - com.apple.CoreSimulator.SimRuntime.tvOS-10-1

tvOS 10.2 (10.2 - 14W260) - com.apple.CoreSimulator.SimRuntime.tvOS-10-2

tvOS 11.0 (11.0 - 15J380) - com.apple.CoreSimulator.SimRuntime.tvOS-11-0

tvOS 11.1 (11.1 - 15J580) - com.apple.CoreSimulator.SimRuntime.tvOS-11-1

tvOS 11.2 (11.2 - 15K104) - com.apple.CoreSimulator.SimRuntime.tvOS-11-2

tvOS 11.3 (11.3 - 15L211) - com.apple.CoreSimulator.SimRuntime.tvOS-11-3

tvOS 11.4 (11.4 - 15L576) - com.apple.CoreSimulator.SimRuntime.tvOS-11-4

watchOS 2.0 (2.0 - 13S343) - com.apple.CoreSimulator.SimRuntime.watchOS-2-0

watchOS 2.1 (2.1 - 13S661) - com.apple.CoreSimulator.SimRuntime.watchOS-2-1

watchOS 2.2 (2.2 - 13V144) - com.apple.CoreSimulator.SimRuntime.watchOS-2-2

watchOS 3.1 (3.1 - 14S471a) - com.apple.CoreSimulator.SimRuntime.watchOS-3-1

watchOS 3.2 (3.2 - 14V243) - com.apple.CoreSimulator.SimRuntime.watchOS-3-2

watchOS 4.0 (4.0 - 15R372) - com.apple.CoreSimulator.SimRuntime.watchOS-4-0

watchOS 4.1 (4.1 - 15R844) - com.apple.CoreSimulator.SimRuntime.watchOS-4-1

watchOS 4.2 (4.2 - 15S100) - com.apple.CoreSimulator.SimRuntime.watchOS-4-2

watchOS 4.3 (4.3 - 15T212) - com.apple.CoreSimulator.SimRuntime.watchOS-4-3

== Devices ==

-- iOS 8.1 --

    iPhone 4s (E145DE0D-8641-4E85-8EAF-C40230E59823) (Shutdown)

    iPhone 5 (9B84F61E-93BD-4AD0-AF99-0E0C81CF26EB) (Shutdown)

    iPhone 5s (4F6013A8-7149-4CA0-8EA5-16397AF05697) (Shutdown)

    iPhone 6 (7A59B747-397E-4481-8E25-301EE292689E) (Shutdown)

    iPhone 6 Plus (D0013AA0-19EB-4AE6-9F1F-6143D0F683C2) (Shutdown)

    iPad 2 (117AEE33-6B9B-4452-8733-AA2A82B435BB) (Shutdown)

    iPad Retina (26C66582-6F21-4D6E-AE69-EC8D156CD888) (Shutdown)

    iPad Air (89F90328-AD88-4577-8736-40780779B263) (Shutdown)

-- iOS 8.2 --

    iPhone 4s (8AABC5C9-6C5F-464D-89CD-B923B4444A64) (Shutdown)

    iPhone 5 (D5A50F84-EB7B-4F0D-AEE9-AB416423E841) (Shutdown)

    iPhone 5s (EFDB60FD-245A-41FC-B6D9-E9E7A49B9D1D) (Shutdown)

    iPhone 6 (15D9386F-E386-4827-9036-94F89CE7E1A8) (Shutdown)

    iPhone 6 Plus (B59628C0-4CA9-4BE5-83DA-4E64D34B3165) (Shutdown)

    iPad 2 (240FE5D6-A78D-48D4-B552-C128E5A85676) (Shutdown)

    iPad Retina (3D5D4969-FFE1-4C60-A73E-9EBF113B8AA5) (Shutdown)

    iPad Air (E5AFD716-008F-47E8-B260-7DDE2341E95F) (Shutdown)

-- iOS 8.3 --

    iPhone 4s (63F40A90-299B-4C7D-B1C9-EA88224D54DB) (Shutdown)

    iPhone 5 (00E85FD1-61CF-4FE5-AF5F-D443327BB161) (Shutdown)

    iPhone 5s (82441DC5-1BC7-41C9-BD12-195E1738D1A7) (Shutdown)

    iPhone 6 (3211A352-AD5C-4FBD-AE57-17B0A2BE5E86) (Shutdown)

    iPhone 6 Plus (778A87FF-8435-4D00-AFCC-2A00BF06C872) (Shutdown)

    iPad 2 (E7D8CA87-CA87-4578-8AA7-B99509F8EAE2) (Shutdown)

    iPad Retina (D4528350-0A78-4CA9-9004-CF1B2964D7F8) (Shutdown)

    iPad Air (28FB9078-A33F-463F-A019-AD258FFF8411) (Shutdown)

-- iOS 8.4 --

    iPhone 4s (92003015-4C0E-481F-B6A9-302F7B8FF3AE) (Shutdown)

    iPhone 5 (6FFEE319-601B-4765-BB82-CB54324FB413) (Shutdown)

    iPhone 5s (9FD77AAE-27F6-4E63-A1A1-C6ED492460DF) (Shutdown)

    iPhone 6 (951D1E23-A48A-4C7F-A204-D422EB72E612) (Shutdown)

    iPhone 6 Plus (0CFA50F1-A050-4511-A509-E7AAEE15C731) (Shutdown)

    iPad 2 (397319BA-1D3A-4FFC-954D-E2AC04E0630A) (Shutdown)

    iPad Retina (6FC55E75-E7E3-46FA-8EFB-6BFAADA4F35C) (Shutdown)

    iPad Air (A65669E3-9C1D-454D-978A-45F5BFC24615) (Shutdown)

-- iOS 9.0 --

    iPhone 4s (E55428B9-4087-44E1-B1EE-4C618D11A0AA) (Shutdown)

    iPhone 5 (DA2BE94F-AF6E-49D0-9FBB-511B3862DA44) (Shutdown)

    iPhone 5s (B7B91829-6B32-4370-9A78-E74742FCD38C) (Shutdown)

    iPhone 6 (8B3254DD-6328-48E5-9F93-B30CA54E7659) (Shutdown)

    iPhone 6 Plus (65914EAD-A89D-4208-85D6-8306A02BA954) (Shutdown)

    iPhone 6s (60028C2C-45E2-4B86-8D2F-CC58AFF29CE1) (Shutdown)

    iPhone 6s Plus (758D589A-1FEE-4204-BDD5-A71F93FC8459) (Shutdown)

    iPad 2 (F51C9E50-1498-4FCD-82A5-95D9B9DDD04D) (Shutdown)

    iPad Retina (C860DDB0-4F9B-45E4-BD0C-B69F8DBA745F) (Shutdown)

    iPad Air (8AC57345-77EC-4CEC-812B-8CB2B95220ED) (Shutdown)

    iPad Air 2 (42277D3E-E496-4326-BBB6-7D0214FFE099) (Shutdown)

-- iOS 9.1 --

    iPhone 4s (D8E31848-E188-4588-AC29-51FAF4C1A370) (Shutdown)

    iPhone 5 (F90D21DF-0BEC-4E8E-AD81-B66BFDB046FF) (Shutdown)

    iPhone 5s (04152D8B-9224-41D3-A464-C08090E81938) (Shutdown)

    iPhone 6 (27651792-73C3-431B-BE9E-798CC2641280) (Shutdown)

    iPhone 6 Plus (42A2D983-6747-4B54-8550-09F23FD5C452) (Shutdown)

    iPhone 6s (4B23C1E8-A8AB-40D1-8EB3-CE06E6FA2BB7) (Shutdown)

    iPhone 6s Plus (97961EC2-1DB6-4BFC-BC73-18A0B83C1C6A) (Shutdown)

    iPad 2 (DC934C3F-B719-4E42-A3BB-83D6EA5586EE) (Shutdown)

    iPad Retina (F4504983-90F2-461C-8D33-D8EF551BD5BF) (Shutdown)

    iPad Air (FD2F94DC-11D9-4E8B-9161-BD7255840D81) (Shutdown)

    iPad Air 2 (053A8D94-AEE5-42B6-BDCD-B5480D51B883) (Shutdown)

    iPad Pro (2AF6B774-0077-4CDE-AC38-42D5C45C50CA) (Shutdown)

-- iOS 9.2 --

    iPhone 4s (A0DCDCF9-8F89-4913-89BD-E90BED1457FE) (Shutdown)

    iPhone 5 (12BF2AEA-3B7E-4AD5-843B-642743B4DEFA) (Shutdown)

    iPhone 5s (CD7FA290-0696-49C6-91FC-3EDD1C42AE54) (Shutdown)

    iPhone 6 (8203DB47-C45B-4005-8716-621862A5DD8D) (Shutdown)

    iPhone 6 Plus (7008DD56-1E26-4FA0-A15E-6360EDCDCE96) (Shutdown)

    iPhone 6s (08CCA0AF-DC79-42AD-8903-202F45ABC76A) (Shutdown)

    iPhone 6s Plus (5740955C-8626-431A-A758-5710FE545359) (Shutdown)

    iPad 2 (A8FD9DFB-3BA9-4F37-9786-918A8040A1D0) (Shutdown)

    iPad Retina (869490D1-5D88-49CA-A717-7E5661D39F92) (Shutdown)

    iPad Air (8E3E6A54-003C-4E75-BF73-A8E27C564F1B) (Shutdown)

    iPad Air 2 (137BBC87-B0B0-4857-AEFA-363A05D0EB0B) (Shutdown)

    iPad Pro (1CDDFF14-C310-4C2B-A97B-3BD2C6AAB370) (Shutdown)

-- iOS 9.3 --

    iPhone 4s (5BF72836-8568-4EC9-BE09-13837A9AF29B) (Shutdown)

    iPhone 5 (E4416F1A-2C29-4E09-80EE-B8E33E00E672) (Shutdown)

    iPhone 5s (ADBF8974-3F87-4E42-93D3-934E1B0F24D5) (Shutdown)

    iPhone 6 (D371393B-143D-423A-86AC-3DEB2191ADED) (Shutdown)

    iPhone 6 Plus (6EED02D9-2574-4954-8420-6FB08A5D7662) (Shutdown)

    iPhone 6s (63443857-BE68-470A-8C29-10A68406EA4B) (Shutdown)

    iPhone 6s Plus (BA8EDC25-9EC9-42BC-8AE4-1115909AF2FA) (Shutdown)

    iPad 2 (3CDE50A2-E43C-4A1C-9774-40B122108FCD) (Shutdown)

    iPad Retina (C643E6ED-6AAF-4DA1-9D6A-113D017AB218) (Shutdown)

    iPad Air (20D55ECB-BE39-447D-99E7-8D22AAB73FC5) (Shutdown)

    iPad Air 2 (9255F0BA-5FD5-4A9C-A32B-C16BEC19474E) (Shutdown)

    iPad Pro (49F82808-6820-443C-AE54-46563B3B4A3C) (Shutdown)

-- iOS 10.0 --

    iPhone 5 (CE64C1D1-2941-494E-9776-F163A273A985) (Shutdown)

    iPhone 5s (1E9E38B6-7943-42FD-8C41-8CF0D4CC1604) (Shutdown)

    iPhone 6 (E3033539-5028-4FD4-AA16-653FC37CEE4F) (Shutdown)

    iPhone 6 Plus (D77996D3-BC74-47E3-B0B3-857BCFB1E6AF) (Shutdown)

    iPhone 6s (A3A57FB5-C0B9-4CA7-865E-F7779B924975) (Shutdown)

    iPhone 6s Plus (7041C612-C9B2-4122-BCC5-A400E10AAAB0) (Shutdown)

    iPhone SE (5D09570A-A1FE-498E-B05F-D05F9C0F4020) (Shutdown)

    iPad Air (56134955-89C0-4C66-AD1C-F03BDF80A8B6) (Shutdown)

    iPad Air 2 (A449EE34-C10C-4466-BC55-F371F0A94E3A) (Shutdown)

    iPad Pro (9.7 inch) (A9CBBF0A-E21E-4EF2-86E2-F22E12C42CF4) (Shutdown)

    iPad Pro (12.9 inch) (6140337D-E25E-4EDF-9162-966417705F77) (Shutdown)

-- iOS 10.1 --

    iPhone 5 (1D3EDE7C-4249-40AD-BAE5-40D7A239183B) (Shutdown)

    iPhone 5s (7A15B00D-056F-423C-A6D7-E1CC9FFD69F5) (Shutdown)

    iPhone 6 (6511E9C7-E650-432C-B297-F5D4498F385F) (Shutdown)

    iPhone 6 Plus (B39CE01F-DB88-4A02-A270-2C1C884567F6) (Shutdown)

    iPhone 6s (7B6E693D-CA53-4894-99D8-C859F1002C74) (Shutdown)

    iPhone 6s Plus (5B3E6A92-DF23-43E2-8992-CC169712A91B) (Shutdown)

    iPhone 7 (00E7C4E5-C9FD-4C22-A9F4-7A414FCEB40F) (Shutdown)

    iPhone 7 Plus (D2114C0B-0853-4757-9592-D8A085710E70) (Shutdown)

    iPhone SE (C50FC40A-4B87-4FB9-8CCC-7C03DEDD1082) (Shutdown)

    iPad Air (15644559-1DB3-4E2F-BCD3-16A70ADD046C) (Shutdown)

    iPad Air 2 (F93E740D-DBAE-43C5-AB3F-81B5F8AF82ED) (Shutdown)

    iPad Pro (9.7 inch) (345492F4-8956-4B22-8C47-E979C8B1C430) (Shutdown)

    iPad Pro (12.9 inch) (758D0FAF-CAD9-421E-81A7-A4EB0C690FBA) (Shutdown)

-- iOS 10.2 --

    iPhone 5 (3B3C20C4-8C82-4CA8-9038-5AECE00787BD) (Shutdown)

    iPhone 5s (A2400270-8AC2-4559-AE1B-E9BE18419E90) (Shutdown)

    iPhone 6 (2F4F50F8-EF24-4117-8F48-4A5C11D2CA32) (Shutdown)

    iPhone 6 Plus (DA901EC3-95E5-444D-91F0-421374C97B61) (Shutdown)

    iPhone 6s (9B4ABE14-2929-4C57-9315-B39700CD6656) (Shutdown)

    iPhone 6s Plus (B5D12611-7D74-4AC2-B391-A080F24F88B7) (Shutdown)

    iPhone 7 (1C771F81-C9C3-43F4-A033-6100AB22F87D) (Shutdown)

    iPhone 7 Plus (B7A86ABE-32AD-4E3E-86CE-37DD98A2056F) (Shutdown)

    iPhone SE (534F4885-01D5-477D-BE7B-5F3648523DF7) (Shutdown)

    iPad Air (CBEB649F-815B-4778-A19C-59DE03B94F7D) (Shutdown)

    iPad Air 2 (CBCC54C2-0152-439D-8ACB-502D3AEE0D3F) (Shutdown)

    iPad Pro (9.7 inch) (25BAB1EE-C38B-4B79-829D-D10858144C66) (Shutdown)

    iPad Pro (12.9 inch) (0A9F05E3-49A9-416D-965D-E21701D7206D) (Shutdown)

-- iOS 10.3 --

    iPhone 5 (78C70CFE-9358-4F34-A294-574E33FE3B24) (Shutdown)

    iPhone 5s (53834BC8-588C-4211-8E51-56D4851F87A5) (Shutdown)

    iPhone 6 (571A28A9-A860-4981-81DB-E49575D14EA1) (Shutdown)

    iPhone 6 Plus (84144717-536F-4356-B570-8E400743F9CF) (Shutdown)

    iPhone 6s (CFE142A3-1088-4246-981D-F0450568AD40) (Shutdown)

    iPhone 6s Plus (0B1D537B-BFB8-4469-AC2B-47247418A543) (Shutdown)

    iPhone 7 (02BA93B0-B437-424C-A0E6-1E7C016D99C4) (Shutdown)

    iPhone 7 Plus (6AF38BC8-2993-4C8A-8360-4ABD65D5FB98) (Shutdown)

    iPhone SE (839B0DCB-4DE3-4D90-BA84-8ED26517A052) (Shutdown)

    iPad Air (6F180D21-E03A-4988-AE77-30AEB26D6E6D) (Shutdown)

    iPad Air 2 (4C47E132-B649-4613-827D-A298003ABA7B) (Shutdown)

    iPad (5th generation) (281EE567-7C49-4C80-B860-7038840D6C17) (Shutdown)

    iPad Pro (9.7 inch) (24E8A5F5-0A59-4A85-9054-2F6B7E24761D) (Shutdown)

    iPad Pro (12.9 inch) (8B3738ED-F803-46EC-9C8D-74E8A54700F0) (Shutdown)

    iPad Pro (12.9-inch) (2nd generation) (A3E32ED0-CAD2-4349-9F34-8D656107A558) (Shutdown)

    iPad Pro (10.5-inch) (E142A5F7-691D-41F0-A341-634CB0870FBC) (Shutdown)

-- iOS 11.0 --

    iPhone 5s (EC845964-3326-4B60-A3DC-51374AED4414) (Shutdown)

    iPhone 6 (EC96BFB8-F9EC-48D2-B48C-A9F7CEECADDA) (Shutdown)

    iPhone 6 Plus (943D96BC-B39F-4E0E-BB3B-6261A7F8A51D) (Shutdown)

    iPhone 6s (690C3DCF-3DC9-47CE-B52D-13AF096D19D3) (Shutdown)

    iPhone 6s Plus (F0DD277D-3661-45E6-ABE5-FCD8F90FE16C) (Shutdown)

    iPhone 7 (E5357DCF-74FB-4268-8606-F50CA97099E7) (Shutdown)

    iPhone 7 Plus (C8956703-437C-4A6A-9D4C-7AD09CBCB019) (Shutdown)

    iPhone 8 (6DB3C9DA-E178-4714-8B6D-1378D8FB112B) (Shutdown)

    iPhone 8 Plus (6923BBD8-4D98-43B7-AA99-7F744E2589E7) (Shutdown)

    iPhone SE (64B19BDF-A160-4DC1-9D55-81BE461F60C7) (Shutdown)

    iPhone X (3E102A0A-BE4F-46AB-ADA7-BC2306A85CD7) (Shutdown)

    iPad Air (17112C49-E13C-4D84-BAAF-242A8C67E65A) (Shutdown)

    iPad Air 2 (D9ED5EF3-BFAB-4C75-999F-00494EBB9F02) (Shutdown)

    iPad (5th generation) (4D0FB9E4-E0A2-4900-A9E9-83ADD8A65AD5) (Shutdown)

    iPad Pro (9.7-inch) (14C10567-E201-4F86-B8F0-782ED860B4EA) (Shutdown)

    iPad Pro (12.9-inch) (F82A3026-4881-42ED-AC9F-312F462D03B6) (Shutdown)

    iPad Pro (12.9-inch) (2nd generation) (345C81BF-73CA-4C62-A46B-F9C58FFF4BEB) (Shutdown)

    iPad Pro (10.5-inch) (E4C355DB-6404-4F69-9BCC-BFB214C21742) (Shutdown)

-- iOS 11.1 --

    iPhone 5s (641E8901-0378-4460-9B93-6D972C15BA7B) (Shutdown)

    iPhone 6 (10DBA2C6-5977-4E68-A962-CEDA32017F48) (Shutdown)

    iPhone 6 Plus (56307E91-5845-4FF9-80D8-18B5CBFB8722) (Shutdown)

    iPhone 6s (C57BF8F5-7C65-4FB0-8662-195E4FEC793C) (Shutdown)

    iPhone 6s Plus (B9CE6497-25B4-4BC0-83EE-D9F453A004EC) (Shutdown)

    iPhone 7 (30C65F35-269F-45A6-8222-ED0E50D3D4A1) (Shutdown)

    iPhone 7 Plus (658662B6-E687-4D2A-9433-DC4EB70ADFFD) (Shutdown)

    iPhone 8 (47F19841-296A-4FB4-B739-DB8423B2E171) (Shutdown)

    iPhone 8 Plus (E6CB8E5B-2F94-4BFC-943F-CED02590B08D) (Shutdown)

    iPhone SE (3DC30833-7E64-499A-A5D2-629FAA2F549A) (Shutdown)

    iPhone X (19C04E45-8476-4245-BE6D-6B7030AA3500) (Shutdown)

    iPad Air (303C2AB9-9237-44FE-9F10-18E12CE102F3) (Shutdown)

    iPad Air 2 (2719F964-04C1-4820-8E2F-2E4DA10F22A4) (Shutdown)

    iPad (5th generation) (C39DBA07-46C8-4D23-9DFF-76C60E778CF2) (Shutdown)

    iPad Pro (9.7-inch) (7F9E4591-8B9B-43EF-9D1F-4DB2DCCB0E71) (Shutdown)

    iPad Pro (12.9-inch) (34617988-12CB-4093-89EC-AB1293898E07) (Shutdown)

    iPad Pro (12.9-inch) (2nd generation) (751156D2-4972-4B17-92A5-DEA45A448A6D) (Shutdown)

    iPad Pro (10.5-inch) (906B4EF2-123D-4E9E-8356-F5178F42B019) (Shutdown)

-- iOS 11.2 --

    iPhone 5s (6E176E5B-393C-4C36-AFDA-31E9B85CE4EC) (Shutdown)

    iPhone 6 (238A7E3B-ABE5-4075-9106-BBD340828C0B) (Shutdown)

    iPhone 6 Plus (F1065747-CA0D-454C-A775-B1B09AFE6FC7) (Shutdown)

    iPhone 6s (ED8B807E-2EB9-4AFC-98D2-574FEA52C700) (Shutdown)

    iPhone 6s Plus (D3030D47-3B2D-447F-BD14-7982C8EDC780) (Shutdown)

    iPhone 7 (AD9B7555-825E-4F92-9168-7D2F95A9F70B) (Shutdown)

    iPhone 7 Plus (BE91A5F3-C6ED-4B02-A449-682E175624D2) (Shutdown)

    iPhone 8 (F122E59C-EFEF-4991-A745-B8F15B32F334) (Shutdown)

    iPhone 8 Plus (31CC51D0-044F-449F-8826-5D58343E54A3) (Shutdown)

    iPhone SE (8ABF65EA-5499-4EA8-B1B2-87788D4A7A77) (Shutdown)

    iPhone X (2DE1B0D5-B570-46B7-8E6C-48AC06B16727) (Shutdown)

    iPad Air (358A4F80-08BC-41B4-B3F9-A7637B14DDBD) (Shutdown)

    iPad Air 2 (08CF7446-575A-4C9D-8274-E7E68347D0BC) (Shutdown)

    iPad (5th generation) (55F7995A-0A8A-496A-87BE-3DC1804A6F8F) (Shutdown)

    iPad Pro (9.7-inch) (34262073-3D0D-42B1-B767-430C3F6E32D1) (Shutdown)

    iPad Pro (12.9-inch) (6BAF52B3-0ADD-4965-9898-8C856932062E) (Shutdown)

    iPad Pro (12.9-inch) (2nd generation) (FD51D415-23B8-41E9-BFCE-C293C19AC42F) (Shutdown)

    iPad Pro (10.5-inch) (7A1DD518-7CF8-49C8-9FE4-14DA9D8E1801) (Shutdown)

-- iOS 11.3 --

    iPhone 5s (13915325-FA77-4D1A-8878-8F01F4CBB778) (Shutdown)

    iPhone 6 (52EB87AB-CFE9-4B4D-ABF3-6668FA51A106) (Shutdown)

    iPhone 6 Plus (8CB8903D-564F-4B52-9FA4-523C8EDB7DA4) (Shutdown)

    iPhone 6s (D73B4B06-CCE1-4E68-A630-5DA61B400573) (Shutdown)

    iPhone 6s Plus (5C83D35E-D7BD-486E-8CEC-0FBCABB59989) (Shutdown)

    iPhone 7 (191AACA4-EF8A-4B25-B0E4-20AD57F98C34) (Shutdown)

    iPhone 7 Plus (90671981-301F-4739-9991-F72AB4F1B9EF) (Shutdown)

    iPhone 8 (5BBD8E1A-FD44-4634-ACB6-8AAE84DA8B81) (Shutdown)

    iPhone 8 Plus (59FE6F20-B97C-42A3-9F47-B761AB0CD3FF) (Shutdown)

    iPhone SE (6E14BA33-86EF-456B-A976-1E8C41337A69) (Shutdown)

    iPhone X (55EA66AD-4E70-411C-9140-3309F33893DB) (Shutdown)

    iPad Air (424DF69C-AC62-4EE4-A6E1-3A137A284822) (Shutdown)

    iPad Air 2 (B57D67C8-3BA8-40BE-AD04-DF62D54C7DC8) (Shutdown)

    iPad (5th generation) (8ED7AD4C-9DF2-43C7-A25C-8E3AEFF0ACE7) (Shutdown)

    iPad Pro (9.7-inch) (1B6EB1F7-2664-42EB-95D9-6E2D17A154B1) (Shutdown)

    iPad Pro (12.9-inch) (92B08AA3-61DE-44D2-A8B8-A7362F921BBC) (Shutdown)

    iPad Pro (12.9-inch) (2nd generation) (BFE9A28C-E2C8-426D-831D-90B16FC61D0D) (Shutdown)

    iPad Pro (10.5-inch) (7C6BF4B4-644F-4109-B30D-694C72A301B4) (Shutdown)

-- iOS 11.4 --

    iPhone 5s (52811967-F70D-4308-B0F7-EC206374504F) (Shutdown)

    iPhone 6 (10BA4146-4DAA-41A4-A4A7-00772CE7673E) (Shutdown)

    iPhone 6 Plus (40945AC1-9BE0-4FBC-BC97-EFB1763B5DBA) (Shutdown)

    iPhone 6s (0D585573-2E18-4664-B29D-C6C9980D43D1) (Shutdown)

    iPhone 6s Plus (70B1FBC5-1123-4954-8812-14BA9A37379A) (Shutdown)

    iPhone 7 (900F4BEF-5D84-45C2-B6DD-2C7FCE515C98) (Shutdown)

    iPhone 7 Plus (EA06DFD7-9FC5-459A-9535-F5D2B4798FE4) (Shutdown)

    iPhone 8 (7AC6E698-B459-437D-AEBC-7CAB855F3008) (Shutdown)

    iPhone 8 Plus (7AE228C0-F5A0-498F-AD42-60B7E51695E2) (Shutdown)

    iPhone SE (7C8840A4-989B-4BF6-90BE-5319DAE5370A) (Shutdown)

    iPhone X (1CED7FFD-E495-4BFD-B866-8A0EB1844B03) (Shutdown)

    iPad Air (889862BA-1837-4A30-8BD4-7F69516ED387) (Shutdown)

    iPad Air 2 (78E55070-B398-43B7-93B0-67AFAC97793C) (Shutdown)

    iPad (5th generation) (87AAAEC5-D8CC-4140-B260-0654E66404F7) (Shutdown)

    iPad Pro (9.7-inch) (7F32A651-7769-4FA4-B0B4-D9909B732A8E) (Shutdown)

    iPad Pro (12.9-inch) (9A70D85F-5B67-4BE4-AA6B-362C36842E1B) (Shutdown)

    iPad Pro (12.9-inch) (2nd generation) (DF65CF2C-D4AA-4749-9476-8ED7FC8186C4) (Shutdown)

    iPad Pro (10.5-inch) (88C92BC2-D1EB-4456-9B63-0FF0766E12F8) (Shutdown)

-- tvOS 9.0 --

    Apple TV 1080p (D780D5A8-F0D0-47B0-883A-464952D2CBD5) (Shutdown)

-- tvOS 9.1 --

    Apple TV 1080p (F50BC5AA-8CD5-496C-99DD-5B27B1DEA70D) (Shutdown)

-- tvOS 9.2 --

    Apple TV 1080p (A6E56DA2-F4E3-4322-A627-495744E86628) (Shutdown)

-- tvOS 10.0 --

    Apple TV 1080p (F9319402-97BD-4DFF-B058-5DB28AE21184) (Shutdown)

-- tvOS 10.1 --

    Apple TV 1080p (0C3C5036-4A65-44C0-B1D2-4005B2F99ECF) (Shutdown)

-- tvOS 10.2 --

    Apple TV 1080p (F5A1CDFA-A178-491F-B7CE-82DE46198977) (Shutdown)

-- tvOS 11.0 --

    Apple TV (CC9DA4FB-3738-450A-90A8-EC032AFFBAEC) (Shutdown)

    Apple TV 4K (CEF678E7-B79F-4E40-8C63-518919C7F9F7) (Shutdown)

    Apple TV 4K (at 1080p) (D3FC3B11-D2B8-44DD-B415-86220D1E4D89) (Shutdown)

-- tvOS 11.1 --

    Apple TV (BAF2A4E6-B69A-4FDF-BC8B-DF7B317D36E2) (Shutdown)

    Apple TV 4K (30CC8568-F39C-4583-AFB1-56A5C1C2E577) (Shutdown)

    Apple TV 4K (at 1080p) (BB7BCDED-72F1-4D2E-904C-B8001EB676C1) (Shutdown)

-- tvOS 11.2 --

    Apple TV (2F2199EF-3367-482F-9625-3E2BBD65A501) (Shutdown)

    Apple TV 4K (73E5B6DF-92BC-4D46-B61B-2C1AD7BD6288) (Shutdown)

    Apple TV 4K (at 1080p) (59013C6B-1775-490A-98DF-8DF0959265FF) (Shutdown)

-- tvOS 11.3 --

    Apple TV (8447579E-9CB0-4999-9E5F-9BF47894D701) (Shutdown)

    Apple TV 4K (96041B2D-3FC5-4248-92B7-213855AF7F83) (Shutdown)

    Apple TV 4K (at 1080p) (42FE02F0-15D6-4247-BE1A-EE7E19719A63) (Shutdown)

-- tvOS 11.4 --

    Apple TV (65EAABD6-89FE-4ED4-864F-0472928DC1E2) (Shutdown)

    Apple TV 4K (AB2B1972-7B19-4860-9609-B9FCDDB9AA68) (Shutdown)

    Apple TV 4K (at 1080p) (54655CFD-C8A0-4A78-A6AE-017BF118FF68) (Shutdown)

-- watchOS 2.0 --

    Apple Watch - 38mm (A13185F0-A7A1-453B-9682-816E81096BB0) (Shutdown)

    Apple Watch - 42mm (582C81B6-1C7D-49F5-9EC4-A28F5DC57F45) (Shutdown)

-- watchOS 2.1 --

    Apple Watch - 38mm (A44CC948-E105-4EAD-AFBD-870151905481) (Shutdown)

    Apple Watch - 42mm (8C49D5C4-B0AA-4BA0-9780-18527BC52540) (Shutdown)

-- watchOS 2.2 --

    Apple Watch - 38mm (6BCF83E2-E919-4FF0-96A0-1158B02AF77E) (Shutdown)

    Apple Watch - 42mm (F7C6CCC0-01FF-4863-AD1D-50CAAA89AA48) (Shutdown)

-- watchOS 3.1 --

    Apple Watch - 38mm (F1209C9B-7B18-4CA7-AEE9-919F5B06B07A) (Shutdown)

    Apple Watch - 42mm (63DE8052-84FE-4E48-9513-D40693154F94) (Shutdown)

    Apple Watch Series 2 - 38mm (3D267CE5-B08B-4DA5-898A-40426021D3D3) (Shutdown)

    Apple Watch Series 2 - 42mm (A69827ED-6386-4D5C-821B-F04789F30F09) (Shutdown)

-- watchOS 3.2 --

    Apple Watch - 38mm (7FD98460-0F61-4B84-8535-6D80B2E116C0) (Shutdown)

    Apple Watch - 42mm (C9714A8D-E71B-4A73-9B12-B5807B825D96) (Shutdown)

    Apple Watch Series 2 - 38mm (A5E5FBCF-3C24-4845-ACD7-842B2F882D1A) (Shutdown)

    Apple Watch Series 2 - 42mm (C7FCDCDB-20F0-4EDD-9267-4E4A33442E59) (Shutdown)

-- watchOS 4.0 --

    Apple Watch - 38mm (1F33916C-E232-44FF-8485-C442215072EB) (Shutdown)

    Apple Watch - 42mm (73FD776F-8F25-408D-829F-8D1FDA969791) (Shutdown)

    Apple Watch Series 2 - 38mm (4EFFF41E-11DB-4C4C-862F-A7C7A23D050F) (Shutdown)

    Apple Watch Series 2 - 42mm (822FC947-AC41-499A-AF07-98E95E799EFB) (Shutdown)

    Apple Watch Series 3 - 38mm (1F253A15-A664-4C70-8570-8F7E4911D7C5) (Shutdown)

    Apple Watch Series 3 - 42mm (DEE4222A-A987-4F76-B129-DB69EB25DA9C) (Shutdown)

-- watchOS 4.1 --

    Apple Watch - 38mm (58F2D9C0-7158-4616-89C2-D78049E5F838) (Shutdown)

    Apple Watch - 42mm (E70FB3E2-7077-4480-A86B-54F0B503A000) (Shutdown)

    Apple Watch Series 2 - 38mm (C40D1764-D25B-41CF-88BC-C8418ABD6D5E) (Shutdown)

    Apple Watch Series 2 - 42mm (D27617BD-4198-4111-B346-8C1DA0593688) (Shutdown)

    Apple Watch Series 3 - 38mm (446666B7-CEAF-400C-B2C5-537B7B745C0F) (Shutdown)

    Apple Watch Series 3 - 42mm (39FB641C-707A-48F0-830D-D6475D97D6E5) (Shutdown)

-- watchOS 4.2 --

    Apple Watch - 38mm (7150DF39-A043-4DBE-BB4B-040673E3805A) (Shutdown)

    Apple Watch - 42mm (58C03713-0E55-496D-A8DA-11140CCF5F60) (Shutdown)

    Apple Watch Series 2 - 38mm (C328DEFB-15B1-4CAF-A229-9D54B71719F4) (Shutdown)

    Apple Watch Series 2 - 42mm (61D8FEF4-B0D2-40EA-9861-AAC9F39D3592) (Shutdown)

    Apple Watch Series 3 - 38mm (C2D45EED-0529-42E8-9E27-FF659249C685) (Shutdown)

    Apple Watch Series 3 - 42mm (E825E419-C80D-4664-AA65-6057709467BC) (Shutdown)

-- watchOS 4.3 --

    Apple Watch - 38mm (D38105CE-C61B-4DEC-A1AA-4DC07515877B) (Shutdown)

    Apple Watch - 42mm (21E2566C-C720-4BC0-9343-4532CFE8AD44) (Shutdown)

    Apple Watch Series 2 - 38mm (95B419C9-B1C6-4A00-BE90-4676D1134AFA) (Shutdown)

    Apple Watch Series 2 - 42mm (48185147-4F89-41DF-AA41-D7A11F85BEF1) (Shutdown)

    Apple Watch Series 3 - 38mm (B74DFDBD-AC1B-4F96-8F1C-FE02C4583EFC) (Shutdown)

    Apple Watch Series 3 - 42mm (6F6B334A-75C0-4B83-8438-EA080C44F6A1) (Shutdown)

== Device Pairs ==

6C2C5675-819B-49F5-85F3-22C026D1D838 (active, disconnected)

    Watch: Apple Watch Series 2 - 38mm (95B419C9-B1C6-4A00-BE90-4676D1134AFA) (Shutdown)

    Phone: iPhone 7 (900F4BEF-5D84-45C2-B6DD-2C7FCE515C98) (Shutdown)

563E2C57-304C-4141-8D93-F9CCC4CA9B7F (active, disconnected)

    Watch: Apple Watch Series 2 - 42mm (48185147-4F89-41DF-AA41-D7A11F85BEF1) (Shutdown)

    Phone: iPhone 7 Plus (EA06DFD7-9FC5-459A-9535-F5D2B4798FE4) (Shutdown)

C72C97BB-A193-48C3-B1D9-1BC4C38E5971 (active, disconnected)

    Watch: Apple Watch Series 3 - 38mm (B74DFDBD-AC1B-4F96-8F1C-FE02C4583EFC) (Shutdown)

    Phone: iPhone 8 (7AC6E698-B459-437D-AEBC-7CAB855F3008) (Shutdown)

30929C0D-228E-4E73-8E59-9B261AB8E71F (active, disconnected)

    Watch: Apple Watch Series 3 - 42mm (6F6B334A-75C0-4B83-8438-EA080C44F6A1) (Shutdown)

    Phone: iPhone 8 Plus (7AE228C0-F5A0-498F-AD42-60B7E51695E2) (Shutdown)

travis_fold:end:announce
[0KNo Gemfile found, skipping bundle install



travis_time:start:20e9f57d
[0K$ curl -s https://raw.githubusercontent.com/atom/ci/master/build-package.sh | sh

Downloading latest Atom release on the stable channel...

Using Atom version:

Atom    : 1.56.0

Electron: 9.4.4

Chrome  : 83.0.4103.122

Node    : 12.14.1

Using APM version:

[31mapm[39m  [31m2.5.2[39m

[32mnpm[39m  [32m6.14.8[39m

[34mnode[39m [34m12.4.0[39m [34mx64[39m

[36matom[39m [36m1.56.0[39m

[33mpython[39m [33m2.7.17[39m

[35mgit[39m [35m2.24.1[39m

Downloading package dependencies...

Installing locked modules [31mâœ—

[39m[31m> vscode-ripgrep@1.5.7 postinstall /Users/travis/build/atom/fuzzy-finder/node_modules/vscode-ripgrep

> node ./lib/postinstall.js



Finding release for v11.0.1-2

GET https://api.github.com/repos/microsoft/ripgrep-prebuilt/releases/tags/v11.0.1-2

Downloading from https://api.github.com/repos/microsoft/ripgrep-prebuilt/releases/assets/13800814

Downloading to /var/folders/nz/vv4_9tw56nv9k3tkvyszvwg80000gn/T/vscode-ripgrep-cache-1.5.7/ripgrep-v11.0.1-2-x86_64-apple-darwin.tar.gz

Download options: {"headers":{"user-agent":"vscode-ripgrep","authorization":"token [secure]","accept":"application/octet-stream"}}

statusCode: 302

Following redirect to: https://github-releases.githubusercontent.com/194786020/23986f00-aa0d-11e9-9811-38f5337c1635?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAIWNJYAX4CSVEH53A%2F20210508%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20210508T041019Z&X-Amz-Expires=300&X-Amz-Signature=bdf22686ab3601182b389d86e81f45a833ff8cb71ee76b57de08b65b004ee25b&X-Amz-SignedHeaders=host&actor_id=6125002&key_id=0&repo_id=194786020&response-content-disposition=attachment%3B%20filename%3Dripgrep-v11.0.1-2-x86_64-apple-darwin.tar.gz&response-content-type=application%2Foctet-stream

Download options: {"headers":{"user-agent":"vscode-ripgrep","accept":"application/octet-stream"}}

statusCode: 200

Unzipping to /Users/travis/build/atom/fuzzy-finder/node_modules/vscode-ripgrep/bin

tar xvf exited with 0



> @atom/fuzzy-native@1.1.2 install /Users/travis/build/atom/fuzzy-finder/node_modules/@atom/fuzzy-native

> node-gyp rebuild



  CXX(target) Release/obj.target/fuzzy-native/src/binding.o



x rg

In file included from ../src/binding.cpp:1:

In file included from ../../../nan/nan.h:2884:

../../../nan/nan_typedarray_contents.h:34:43: warning: 'GetContents' is deprecated: Use GetBackingStore. See http://crbug.com/v8/9908. [-Wdeprecated-declarations]

      data   = static_cast<char*>(buffer->GetContents().Data()) + byte_offset;

                                          ^

/Users/travis/.atom/.node-gyp/Library/Caches/node-gyp/9.4.4/include/node/v8.h:5259:3: note: 'GetContents' has been explicitly marked deprecated here

  V8_DEPRECATE_SOON("Use GetBackingStore. See http://crbug.com/v8/9908.")

  ^

/Users/travis/.atom/.node-gyp/Library/Caches/node-gyp/9.4.4/include/node/v8config.h:408:41: note: expanded from macro 'V8_DEPRECATE_SOON'

#   define V8_DEPRECATE_SOON(message) [[deprecated(message)]]

                                        ^

../src/binding.cpp:133:18: error: no matching member function for call to 'Set'

          array->Set(i, New(match.matchIndexes->at(i)));

          ~~~~~~~^~~

/Users/travis/.atom/.node-gyp/Library/Caches/node-gyp/9.4.4/include/node/v8.h:3664:37: note: candidate function not viable: requires 3 arguments, but 2 were provided

  V8_WARN_UNUSED_RESULT Maybe<bool> Set(Local<Context> context,

                                    ^

/Users/travis/.atom/.node-gyp/Library/Caches/node-gyp/9.4.4/include/node/v8.h:3667:37: note: candidate function not viable: requires 3 arguments, but 2 were provided

  V8_WARN_UNUSED_RESULT Maybe<bool> Set(Local<Context> context, uint32_t index,

                                    ^

../src/binding.cpp:137:15: error: no matching member function for call to 'Set'

      result->Set(result_count++, obj);

      ~~~~~~~~^~~

/Users/travis/.atom/.node-gyp/Library/Caches/node-gyp/9.4.4/include/node/v8.h:3664:37: note: candidate function not viable: requires 3 arguments, but 2 were provided

  V8_WARN_UNUSED_RESULT Maybe<bool> Set(Local<Context> context,

                                    ^

/Users/travis/.atom/.node-gyp/Library/Caches/node-gyp/9.4.4/include/node/v8.h:3667:37: note: candidate function not viable: requires 3 arguments, but 2 were provided

  V8_WARN_UNUSED_RESULT Maybe<bool> Set(Local<Context> context, uint32_t index,

                                    ^

../src/binding.cpp:163:30: error: no matching member function for call to 'Get'

        auto id_value = ids->Get(i);

                        ~~~~~^~~

/Users/travis/.atom/.node-gyp/Library/Caches/node-gyp/9.4.4/include/node/v8.h:3711:43: note: candidate function not viable: requires 2 arguments, but 1 was provided

  V8_WARN_UNUSED_RESULT MaybeLocal<Value> Get(Local<Context> context,

                                          ^

/Users/travis/.atom/.node-gyp/Library/Caches/node-gyp/9.4.4/include/node/v8.h:3714:43: note: candidate function not viable: requires 2 arguments, but 1 was provided

  V8_WARN_UNUSED_RESULT MaybeLocal<Value> Get(Local<Context> context,

                                          ^

../src/binding.cpp:166:64: error: no matching member function for call to 'Get'

        auto value = to_std_string(Nan::To<v8::String>(values->Get(i)).ToLocalChecked());

                                                       ~~~~~~~~^~~

/Users/travis/.atom/.node-gyp/Library/Caches/node-gyp/9.4.4/include/node/v8.h:3711:43: note: candidate function not viable: requires 2 arguments, but 1 was provided

  V8_WARN_UNUSED_RESULT MaybeLocal<Value> Get(Local<Context> context,

                                          ^

/Users/travis/.atom/.node-gyp/Library/Caches/node-gyp/9.4.4/include/node/v8.h:3714:43: note: candidate function not viable: requires 2 arguments, but 1 was provided

  V8_WARN_UNUSED_RESULT MaybeLocal<Value> Get(Local<Context> context,

                                          ^

../src/binding.cpp:178:30: error: no matching member function for call to 'Get'

        auto id_value = ids->Get(i);

                        ~~~~~^~~

/Users/travis/.atom/.node-gyp/Library/Caches/node-gyp/9.4.4/include/node/v8.h:3711:43: note: candidate function not viable: requires 2 arguments, but 1 was provided

  V8_WARN_UNUSED_RESULT MaybeLocal<Value> Get(Local<Context> context,

                                          ^

/Users/travis/.atom/.node-gyp/Library/Caches/node-gyp/9.4.4/include/node/v8.h:3714:43: note: candidate function not viable: requires 2 arguments, but 1 was provided

  V8_WARN_UNUSED_RESULT MaybeLocal<Value> Get(Local<Context> context,

                                          ^

1 warning and 5 errors generated.

make: *** [Release/obj.target/fuzzy-native/src/binding.o] Error 1

gyp ERR! build error 

gyp ERR! stack Error: `make` failed with exit code: 2

gyp ERR! stack     at ChildProcess.onExit (/Users/travis/build/atom/fuzzy-finder/atom/Atom.app/Contents/Resources/app/apm/node_modules/npm/node_modules/node-gyp/lib/build.js:194:23)

gyp ERR! stack     at ChildProcess.emit (events.js:200:13)

gyp ERR! stack     at Process.ChildProcess._handle.onexit (internal/child_process.js:272:12)

gyp ERR! System Darwin 17.7.0

gyp ERR! command "/Users/travis/build/atom/fuzzy-finder/atom/Atom.app/Contents/Resources/app/apm/bin/node" "/Users/travis/build/atom/fuzzy-finder/atom/Atom.app/Contents/Resources/app/apm/node_modules/npm/node_modules/node-gyp/bin/node-gyp.js" "rebuild"

gyp ERR! cwd /Users/travis/build/atom/fuzzy-finder/node_modules/@atom/fuzzy-native

gyp ERR! node -v v12.4.0

gyp ERR! node-gyp -v v5.1.0

gyp ERR! not ok 

npm ERR! code ELIFECYCLE

npm ERR! errno 1

npm ERR! @atom/fuzzy-native@1.1.2 install: `node-gyp rebuild`

npm ERR! Exit status 1

npm ERR! 

npm ERR! Failed at the @atom/fuzzy-native@1.1.2 install script.

npm ERR! This is probably not a problem with npm. There is likely additional logging output above.



npm ERR! A complete log of this run can be found in:

npm ERR!     /Users/travis/.atom/.apm/_logs/2021-05-08T04_10_24_181Z-debug.log[39m

Linting package using standard...

sh: line 179: ./node_modules/.bin/standard: No such file or directory

travis_time:end:20e9f57d:start=1620446994802799000,finish=1620447028537936000,duration=33735137000,event=script
[0K[31;1mThe command "curl -s https://raw.githubusercontent.com/atom/ci/master/build-package.sh | sh" exited with 127.[0m





Done. Your build exited with 1.
