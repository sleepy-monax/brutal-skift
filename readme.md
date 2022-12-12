# brutal-skift

🏢+🥑 What you are refering to as skift is in fact brutal+skift

![now-kiss](now-kiss.png)

## What's this?

This is an attempt to run skift on top of the brutal microkernel. It is a work in progress.

## What needs to be done?

 - [ ] operator new(unsigned long)
 - [ ] operator new[](unsigned long)
 - [ ] operator delete[](void*)
 - [ ] Embed::panic(char const*)
 - [ ] Embed::makeHost(Karm::Strong<Karm::Ui::Node>)
 - [ ] Embed::loggerLock()
 - [ ] Embed::loggerOut()
 - [ ] Embed::loggerUnlock()
 - [ ] Embed::memUnmap(void const*, unsigned long)
 - [ ] Embed::memMap(Karm::Sys::MmapOptions const&, Karm::Strong<Karm::Sys::Fd>)
 - [ ] Embed::createIn()
 - [ ] Embed::createOut()
 - [ ] Embed::createErr()
 - [ ] Embed::createFile(Karm::Sys::Path)
 - [ ] Embed::openFile(Karm::Sys::Path)
 - [ ] embed_crypto_entropy
