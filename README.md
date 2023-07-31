# rdd

"Roblox Deployment Downloader" - Static Site for Locally Downloading Roblox (Windows/Mac) Player + Studio Deployments Directly from Your Browser!
<br />
Hosted officially @ <https://rdd.latte.to>

## Usage

```txt
[*] USAGE: https://rdd.latte.to/?channel=<CHANNEL_NAME>&version=<VERSION_GUID>&blobDir=<BLOB_DIR>
    OR
[*] USAGE: https://rdd.latte.to/?channel=<CHANNEL_NAME>&binaryType=<BINARY_TYPE>&blobDir=<BLOB_DIR>

    Binary Types:
    * WindowsPlayer
    * WindowsStudio64
    * MacPlayer
    * MacStudio
    
    Blob Directories (Examples):
    * "/" (Usually for WindowsPlayer/WindowsStudio files)
    * "/mac/"
    * "/mac/arm64/"
    
    Extra Notes:
    * If `channel` isn't provided, it will default to "LIVE" (psuedo identifier for production)
    * If `blobDir` isn't provided, it will default to "/". This query is only used if a specific
      `version` is set, and not if `binaryType` is. (Resolves itself) 
    * EITHER `version` or `binaryType` need to be provided, but never both

```

## Extras

* [Latte Softworks Discord Community](https://latte.to/discord)
* <https://github.com/latte-soft/channel-tracker>

## License

See [LICENSE.txt](LICENSE.txt), or visit <https://www.gnu.org/licenses/gpl-3.0.html>

```
Copyright (C) 2023 Latte Softworks <latte.to>

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.
```
