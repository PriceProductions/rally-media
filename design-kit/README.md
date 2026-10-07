# Moved: this folder now lives in rally-media-confidential

On 2026-10-07 the private working files (design kit, video kit, app screens, job specs and drafts) moved to the **private** repo `PriceProductions/rally-media-confidential`. This public repo (`PriceProductions/rally-media`) now holds only the finished post images and videos in `p/`, because Buffer can only post media from a public link.

What to do instead:
- Clone the private repo (use add_repo with push access if you need it): `git clone --depth 1 https://github.com/PriceProductions/rally-media-confidential` and read the README for the design kit (design-kit/README.md) there. That is the real, current version.
- Read and commit **kit changes, job specs and new templates or photos** (design-kit/..., video-kit/..., screens/...) in `rally-media-confidential`, never in this public repo.
- Real app screens (the old `screens/2026-10-03/`) are in `rally-media-confidential` under `screens/2026-10-03/`.
- Put **only the finished post file** here: `p/<post id>.jpg` or `p/<post id>.mp4`. Then set the post's `publicUrl` / `publicVideo` to `https://raw.githubusercontent.com/PriceProductions/rally-media/main/p/<file>`.
- Never copy kit files, scripts, drafts or screens into this public repo.
