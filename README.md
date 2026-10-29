# Piero

I build [EyeCanSee](https://github.com/IoSonoPiero/eyecansee), an image and video viewer and manager for Linux and Windows written in Rust: it opens folders, disks, servers and Android phones the same way, with no import and no catalogue, and handles the daily work with photos and videos: copy and move between devices, duplicates, conversion, RAW and HEIC. On Linux it reads phones directly over USB, in seconds.

Along the way I contribute to [mtp-rs](https://github.com/vdavid/mtp-rs), the pure-Rust MTP library it is built on: folder listing with `GetObjectPropList` ([#45](https://github.com/vdavid/mtp-rs/pull/45), 12 to 14 times faster on large Android folders), object dates and a kept-open download stream on Windows ([#41](https://github.com/vdavid/mtp-rs/pull/41), [#46](https://github.com/vdavid/mtp-rs/pull/46)), device testing on POCO and Samsung phones.

Twenty years of Linux, Docker and server infrastructure. Italian translator of Nigel Poulton's *Getting Started with Docker*. Notes at [notes.montinaro.info](https://notes.montinaro.info).
