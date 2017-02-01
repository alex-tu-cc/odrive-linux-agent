# cloud aggregator: odrive
 * [odrive](https://www.odrive.com)
 

## Usage:
 * this package is tend to pack odrive agent and client utility in debian packge.
 * Somehow, the odriveagent get failure if the symble be striped, so this package need to be built manuall.
    * ``$ DEB_BUILD_OPTIONS=nostrip debuild -i -b -us -uc``
    * or there is a pre-built package there.
        * https://dl.dropboxusercontent.com/u/2495108/packages/odrive-linux-agent_0.1~916-d0265_amd64.deb
 * [scripts in linux](https://forum.odrive.com/t/odrive-sync-agent-a-cli-scriptable-interface-for-odrives-progressive-sync-engine-for-linux-os-x-and-windows/499)

## Know issues:
 * don't know what's the official from odrive should be:
    * https://forum.odrive.com/t/concurrency-for-small-files-in-linux-not-works-well/1952
