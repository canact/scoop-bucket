# Scoop bucket for canact

Windows packages for [canact](https://github.com/canact/canact).

```powershell
scoop bucket add canact https://github.com/canact/scoop-bucket
scoop install canact/canact
```

Each public GitHub Release rewrites `bucket/canact.json` (version,
URL, and SHA256). That committed JSON is what `scoop install` uses.
The `checkver` field is only a fallback if the push lags.

This bucket is not ScoopInstaller Main or Extras. `scoop search`
only finds the app after you add the bucket.

