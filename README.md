LG Optimus F6 KitKat source for use with the LG Optimus F3
=============

CM11 Kernel tree for LG Optimus F3

Copy the contents of this repo to: kernel/lge/fx3t

Or, alternatively, you can add this to your .repo/local_manifests/ with this template:

```
<?xml version="1.0" encoding="UTF-8"?>
<manifest>
	<remote name="fx3" fetch="https://github.com/" />
	<project path="device/lge/fx3" name="daemon32/android_lge_fx3.git" remote="fx3" revision="master" />
	<project path="kernel/lge/fx3t" name="daemon32/android_kernel_lge_fx3t.git" remote="fx3t" revision="master" />
</manifest>
```

Old git history can be found at https://github.com/daemon32/lge_fx3t_cm11

Enjoy!
