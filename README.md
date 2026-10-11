<p align="center">
  <img src="program_info/com.spectrumcmg.SpectrumLauncher_256.png" width="128" alt="Spectrum Launcher">
</p>

<h1 align="center">Spectrum Launcher</h1>

<p align="center">A Minecraft launcher by <a href="https://spectrumcmg.com">The Spectrum</a> for managing multiple Minecraft installations.</p>

---

> **Spectrum Launcher is a fork of [Prism Launcher](https://prismlauncher.org).**
> It is not Prism Launcher, and it is not endorsed by or affiliated with the Prism Launcher project.

## Download

Grab the latest Windows build from the [Releases](../../releases) page, or from the **Actions** tab (latest build of `develop`):

- `SpectrumLauncher-Windows-MSVC-Setup-…`: installer (recommended)
- `SpectrumLauncher-Windows-MSVC-Portable-…`: portable zip, no install needed

You sign in with your own Microsoft account. A legitimate copy of Minecraft: Java Edition is required.

## Building

Builds run automatically on GitHub Actions (`.github/workflows/build.yml`) on every push to `develop`.
To build locally, follow Prism Launcher's [build instructions](https://prismlauncher.org/wiki/development/build-instructions/) using this repository.

### Repository secrets

| Secret | Purpose |
| --- | --- |
| `MSA_CLIENT_ID` | Azure app (client) ID used for Microsoft account login. **Required for sign-in to work.** |
| `CURSEFORGE_API_KEY` | Optional. Enables CurseForge modpack browsing. |

## License

All launcher code is available under the GPL-3.0-only license (see [LICENSE](LICENSE) and [COPYING.md](COPYING.md)).
Original work © Prism Launcher, PolyMC and MultiMC contributors. Spectrum branding © SCMG B.V.
