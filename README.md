# scoop-zid

Scoop bucket for [zid](https://github.com/gstrainovic/zid), a GPU-accelerated editor with
Markdown preview, PDF viewer and local AI.

```powershell
scoop bucket add zid https://github.com/gstrainovic/scoop-zid
scoop install zid/zid
```

`bucket/zid.json` follows new zid releases on its own: the Excavator workflow runs every
four hours, checks the latest GitHub release (`checkver`) and updates version, URL and hash
(`autoupdate`).
