Upstream LK source: https://github.com/littlekernel/lk

This mtk-specific tree came from https://github.com/svoboda18/lk, and I have no idea where *that* came from.

I'm mostly interested in this source for reverse engineering purposes ("where does dm-verity corrupted error come from?" "how does fastboot oem unlock work?")

I'm also interested in the possibility of using mtkclient to bootstrap a custom kernel *without* making any permanent changes to flash.

I'm intrigued by this patch that supports booting linux from RAM: https://github.com/Gigaset-dev/lk2/commit/ab107ff351cb5550ee2aa92b0b7bc6ac0089befc

# Compiling

Run `make` and then figure out why it didn't work. (TODO: figure this out lol)
