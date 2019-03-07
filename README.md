-----------------------------------------------------------------------------

<p align="center">
<img src="https://github.com/DotOS/manifest/blob/dot-o/About.png" > 
</p>

-----------------------------------------------------------------------------
Credits:
=======
 * [**JDCTeam**](https://github.com/AOSP-JF-MM)
 * [**ABC**](https://github.com/ezio84?tab=repositories)
 * [**DirtyUnicorns**](https://github.com/dirtyunicorns)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**Nitrogen-Project**](https://github.com/nitrogen-project)
 * [**AospExtended**](https://github.com/AospExtended)
 * [**TeamSubstratum (Theme Engine)**](https://github.com/Substratum)
 * [**Shakthivel Nadar**](https://github.com/Sonic-sakthivel123) - Builder
 * [**Dan Santos**](https://github.com/linusdan) - Developer/Fork contribuitor of dotOS for i9300
 * [**Shilin Victor**](https://github.com/ChronoMonochrome) - Developer of Lineage 15.1/16.0 for i9300

-----------------------------------------------------------------------------

Getting Started:
==============

To get started with the building process, you'll need to get familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository, use a command like this:

```bash
    repo init -u git://github.com/DotOS/manifest.git -b dot-o
    git clone https://github.com/dot-i9300/dot-manifests.git -b dot-o .repo/local_manifests
```

Then to sync up:
================

```bash
    repo sync -c -jx --force-sync --no-clone-bundle --no-tags
```

Additionally, you can define the number of parallel download repo should do:

```bash
    repo sync -f -jX --force-sync --no-clone-bundle --no-tags ( X is the number of parallel download repo should do choose depending on your cpu )
```

Compilation of Dot OS:
====================

From root directory of Project, perform following commands in terminal


```bash
source build/envsetup.sh
lunch dot_i9300-userdebug
make bacon
```
-----------------------------------------------------------------------------

Some Links:-
============
* [**Website**](https://www.droidontime.com)
* [**Telegram Public Chat**](https://t.me/dotos)
* [**Telegram Channel**](https://t.me/dotOSchannel)
* [**Facebook Page**](https://www.facebook.com/dotosofficial)
* [**Twitter**](https://twitter.com/dotosofficial)

<p align="center">
<img src="https://github.com/DotOS/manifest/blob/dot-n/dotlogo.png" > 
</p>
