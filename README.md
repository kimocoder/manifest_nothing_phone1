<p align="center">
  <img src="https://i.imgur.com/32ihEhr.png"/>
</p>

### Sync ###
```bash
        repo init -u https://github.com/kimocoder/manifest_nothing_phone1.git -b 15 --git-lfs
        repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Build ###
```bash
	. build/envsetup.sh
        brunch device
```

[![TG chat](https://img.shields.io/badge/Support-Telegram-%23e52c5f.svg?style=for-the-badge&logo=telegram&&labelColor=121217)](https://t.me/voltageos)
