# CHANGELOG

#### 0.1.0 (2019-07-15)

- Initial release.

#### 0.2.0 (2019-09-03)

- Added `patchResourceStatus()` to patch a status object rather than having to set it completely every time.
- Fixed problem with all events running in parallel due to async/await. They are processed consecutively now.

#### 0.3.0 (2019-09-13)

- Removed `watchCustomResource()` as it made little sense to use this in practice due to the required permissions. Just use `watchResource()`.
- Small tweaks.

#### 0.3.1 (2019-09-13)

- Removed `watchCustomResource()` from `README.md`.
- Updated to TypeScript 3.6.3.