![banner](https://raw.githubusercontent.com/JLST-SM-MSM8974/local_manifests/los18/manifest_banner.png)
# Samsung MSM8974 Tree Manifest
This is the manifest to clone the hlte family device trees.

## How to clone trees
### Prerequisites
- Knowledge on how to initialize ROM source
- Familiarity with using [Git](https://www.atlassian.com/git/tutorials/atlassian-git-cheatsheet).
- [Setup](https://github.com/akhilnarang/scripts) build environment. 
    - For Arch users, just install [lineageos-devel](https://aur.archlinux.org/packages/lineageos-devel) and you should be good to go.

## Instructions
### Before sync
- Clone this repostitory inside the `.repo` folder.
    - Since `local_manifests` folder is empty, the manifest stuff will be inside `.repo/local_manifests`.
    ```bash
    cd .repo
    git clone https://github.com/JLST-SM-MSM8974/local_manifests.git -b los18
    ```

### After sync
- Make sure to double check directories and adapt the trees if needed.
- These trees should work as is for most Lineage based ROMs.