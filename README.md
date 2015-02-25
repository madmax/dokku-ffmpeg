# dokku-ffmpeg

## TODO
Couldn't we just copy the binaries straight from the folder on disk rather than using wget?

Install ffmpeg into a dokku container.
Points to an ffmpeg build created for ubuntu using this guide https://trac.ffmpeg.org/wiki/CompilationGuide/Ubuntu.

This plugin is based on the pattern used by https://github.com/F4-Group/dokku-apt.

#### Installing
```
git clone https://github.com/aldenks/dokku-ffmpeg /var/lib/dokku/plugins/dokku-ffmpeg
dokku plugins-install
```
