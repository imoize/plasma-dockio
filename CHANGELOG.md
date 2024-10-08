
## [v0.2.4] - 2024-09-22
### :boom: BREAKING CHANGES
- due to [`92ef409`](https://github.com/imoize/plasmoid-dockio/commit/92ef4091b70ed03370f2d935ecb67d06ec1026da) - Include all icons in package. *(commit by [@imoize](https://github.com/imoize))*:

  No more installation of icon pack separately.

- due to [`d77a882`](https://github.com/imoize/plasmoid-dockio/commit/d77a882ac89d246d0d0215627209434517d2c77e) - Minor refactor. *(commit by [@imoize](https://github.com/imoize))*:

  Refactor may affect app functionality. Reinstall maybe required.


### :sparkles: New Features
- [`5d4551a`](https://github.com/imoize/plasmoid-dockio/commit/5d4551ae1f9f70619a9c9f066546b8fae4e5ad00) - Add shortcut for exec and log. *(commit by [@imoize](https://github.com/imoize))*
- [`4c0eb21`](https://github.com/imoize/plasmoid-dockio/commit/4c0eb21beeb671f60f619f4acf2a4d1c32666e8e) - Add delete confirmation dialog. *(commit by [@imoize](https://github.com/imoize))*

### :bug: Bug Fixes
- [`f6570c4`](https://github.com/imoize/plasmoid-dockio/commit/f6570c4bd1e1541925abb45fe96827364c8b8284) - **Ui**: Fixed statusbar height if no container listed. *(commit by [@imoize](https://github.com/imoize))*
- [`b9aed5c`](https://github.com/imoize/plasmoid-dockio/commit/b9aed5cc19606373cf314d57a8d1337ec1f5ca24) - Fixed progress bar and fetch timer should restore to initial value. *(commit by [@imoize](https://github.com/imoize))*
- [`23106ca`](https://github.com/imoize/plasmoid-dockio/commit/23106cae049daa9c6422f64c4dd77f45ec131631) - Notification icon missing. *(commit by [@imoize](https://github.com/imoize))*

### :recycle: Refactors
- [`92ef409`](https://github.com/imoize/plasmoid-dockio/commit/92ef4091b70ed03370f2d935ecb67d06ec1026da) - **Ui**: Include all icons in package. *(commit by [@imoize](https://github.com/imoize))*
- [`d77a882`](https://github.com/imoize/plasmoid-dockio/commit/d77a882ac89d246d0d0215627209434517d2c77e) - Minor refactor. *(commit by [@imoize](https://github.com/imoize))*

### :wrench: Chores
- [`25bae9c`](https://github.com/imoize/plasmoid-dockio/commit/25bae9c67292aa994cd5ddee5c39bf6fc7648401) - **UI**: Rename "Fetch Container" to "Refresh". *(commit by [@imoize](https://github.com/imoize))*
- [`61d9d89`](https://github.com/imoize/plasmoid-dockio/commit/61d9d8905611f7f67f9c2b2d6337d78cf6a4f23e) - Bump to v0.2.4 *(commit by [@imoize](https://github.com/imoize))*


## [v0.1.1] - 2024-09-02
### :sparkles: New Features
- [`f23cf89`](https://github.com/imoize/plasmoid-dockio/commit/f23cf89603c91cfc8adf350ab68e3ef94a8f7528) - **Ui**: Display total containers and image count in statusbar. *(commit by [@imoize](https://github.com/imoize))*

### :bug: Bug Fixes
- [`32c16b2`](https://github.com/imoize/plasmoid-dockio/commit/32c16b29bc82e8924280af868410516123c6959d) - Fixed highlight not removed when cursor leave window. *(commit by [@imoize](https://github.com/imoize))*

### :wrench: Chores
- [`7d9c512`](https://github.com/imoize/plasmoid-dockio/commit/7d9c512b6665992e47b0f056db09ed068c921813) - **Improvement**: Change first text to uppercase *(commit by [@imoize](https://github.com/imoize))*
- [`35a5de8`](https://github.com/imoize/plasmoid-dockio/commit/35a5de86efee676f951d87dd0ae8b72e002d4b54) - Bump to v0.1.1 *(commit by [@imoize](https://github.com/imoize))*
- [`9a2bc42`](https://github.com/imoize/plasmoid-dockio/commit/9a2bc42ccfa0067c16f2cdfbcdedddba136e1593) - Change url *(commit by [@imoize](https://github.com/imoize))*


## [v0.0.4] - 2024-08-21
### :bug: Bug Fixes
- [`269655c`](https://github.com/imoize/plasma-dockio/commit/269655c2a335828d629cc3bd09da0b919e45fd20) - Resolve issue where fetch container timer might be triggered twice *(commit by [@imoize](https://github.com/imoize))*

### :recycle: Refactors
- [`ba134fc`](https://github.com/imoize/plasma-dockio/commit/ba134fc134c8b5a39006d6dad8c8a695259a5871) - Remove unused import *(commit by [@imoize](https://github.com/imoize))*
- [`a35c04a`](https://github.com/imoize/plasma-dockio/commit/a35c04a148ae23bd417bebf57289529961de9381) - Remove unused property *(commit by [@imoize](https://github.com/imoize))*

### :wrench: Chores
- [`8d6f4e4`](https://github.com/imoize/plasma-dockio/commit/8d6f4e4b863a1b5ea8f36a397b5cb9edbce426d4) - Bump to v0.0.4 *(commit by [@imoize](https://github.com/imoize))*


## [v0.0.3] - 2024-08-10
### :bug: Bug Fixes
- [`0cf0c86`](https://github.com/imoize/plasma-dockio/commit/0cf0c864b6a4de3724c871f577acfdb2957d266d) - Fix prevent null reference errors when navigating away and back *(commit by [@imoize](https://github.com/imoize))*

### :recycle: Refactors
- [`49523e5`](https://github.com/imoize/plasma-dockio/commit/49523e527cfa957ae61de313d9d68564a439da9b) - Simplify and remove unused key handling *(commit by [@imoize](https://github.com/imoize))*

### :wrench: Chores
- [`60a25b8`](https://github.com/imoize/plasma-dockio/commit/60a25b85801e290225db0db35efe3c85e4fa750b) - Bump to v0.0.3 *(commit by [@imoize](https://github.com/imoize))*


## [v0.0.2] - 2024-08-08
### :bug: Bug Fixes
- [`e659245`](https://github.com/imoize/plasma-dockio/commit/e6592451cbfc4819722c548b96e31c12f22a73e1) - Poll API interval not running when initial startup *(commit by [@imoize](https://github.com/imoize))*

[v0.0.2]: https://github.com/imoize/plasma-dockio/compare/v0.0.1...v0.0.2
[v0.0.3]: https://github.com/imoize/plasma-dockio/compare/v0.0.2...v0.0.3
[v0.0.4]: https://github.com/imoize/plasma-dockio/compare/v0.0.3...v0.0.4
[v0.1.1]: https://github.com/imoize/plasmoid-dockio/compare/v0.0.4...v0.1.1
[v0.2.4]: https://github.com/imoize/plasmoid-dockio/compare/v0.1.1...v0.2.4
