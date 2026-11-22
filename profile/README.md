<p align="center">
  <img src="nilperit-mark.svg" alt="NilPerit logo: four layers with a keyhole" width="120">
</p>

<h1 align="center">NilPerit</h1>

<p align="center">
  <em>Omnia mutantur, nihil interit.</em> Everything changes, nothing perishes. (Ovid)
</p>

NilPerit is a personal backup system. It pulls your data from cloud accounts and local folders into an encrypted, versioned vault that you control. When something happens in the cloud, your data is still here.

- **Nothing is lost.** Deleting or changing something at the source never removes it from your vault. Only the retention rules you set can do that.
- **Your keys, your data.** Everything is encrypted with keys derived from a 24-word recovery phrase that only you hold. A server running NilPerit can add to your backup but cannot read it.
- **Readable without us.** Every vault carries its own format specification and reader software. With your recovery phrase and any surviving copy, you can get your data back, even if this project no longer exists.
- **Efficient.** Content is deduplicated across sources and versions, so an edit stores only what changed.

## Status

**Pre-alpha.** The storage format is a draft and the code is just starting. Do not use NilPerit for real data yet. See the [roadmap](https://github.com/nilperit/nilperit/blob/main/docs/roadmap.md) for what comes next.

## Learn more

- [nilperit/nilperit](https://github.com/nilperit/nilperit): the code
- [How the format fits together](https://github.com/nilperit/nilperit/blob/main/docs/overview.md): an informal explainer with diagrams
- [Design decisions](https://github.com/nilperit/nilperit/tree/main/docs/decisions): why NilPerit works the way it does
- [Security policy](https://github.com/nilperit/nilperit/blob/main/SECURITY.md): how to report a vulnerability

NilPerit is open source under the [MIT license](https://github.com/nilperit/nilperit/blob/main/LICENSE).