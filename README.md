# zip-3588-zdyz

`01、linux_sdk.zip` is about 6.1 GB, so it has been split into 127 parts in the `parts/` directory for regular Git upload.

Parts:

- `parts/linux_sdk.zip.part-000` to `parts/linux_sdk.zip.part-126`
- Most parts are about 49 MiB
- The last part is about 21 MiB

Rebuild on Linux/macOS:

```bash
cat parts/linux_sdk.zip.part-* > "01、linux_sdk.zip"
```

Rebuild on Windows with Git Bash:

```bash
cat parts/linux_sdk.zip.part-* > "01、linux_sdk.zip"
```
