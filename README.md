> [!IMPORTANT]
> This is a fork of `opencat.app` with redesign.  
> **Status: Merged**  
> [See pull request](https://github.com/waylybaye/opencat.app/pull/29)

# Redesign OpenCat website
## Preview
- **Demo at: https://opencat.xatloon.com/**

- [PageSpeed Insights Report from Oct 12, 2023, 1:26:07 PM](https://pagespeed.web.dev/analysis/https-opencat-xatloon-me/xor94klsju?form_factor=mobile)

<img width="400" alt="pagespeed" src="https://github.com/waylybaye/opencat.app/assets/54651817/41b24bfb-5c9a-4efe-aa35-42b4d727b453">

### After
<img src="https://github.com/waylybaye/opencat.app/assets/54651817/f9d14817-35ea-4dc3-b171-81c1e1fab351" alt="light" width="400" /><img src="https://github.com/waylybaye/opencat.app/assets/54651817/8875c8ca-1a6e-4613-ad97-1d3cb54c8955" alt="dark" width="400" />

**Show More**

<details>
<summary>Smart App Banners</summary>
<img width="400" alt="smart app banner" src="https://github.com/waylybaye/opencat.app/assets/54651817/71241b46-f723-498a-b446-99143767c83d">
</details>

<details>
<summary>Menu</summary>
<img width="400" alt="header" src="https://github.com/waylybaye/opencat.app/assets/54651817/a1b78e3f-1860-41e0-a586-5b80901c51a3d">
</details>

<details>
<summary>Sections</summary>
<img width="400" alt="screenshots" src="https://github.com/waylybaye/opencat.app/assets/54651817/8b2c0b6c-e727-4973-aa4c-f18da260542f">
<img width="400" alt="features" src="https://github.com/waylybaye/opencat.app/assets/54651817/a4b7005e-d0b4-4de8-adce-ebe99b41c31b">
<img width="400" alt="resources" src="https://github.com/waylybaye/opencat.app/assets/54651817/ff6bd792-8dcf-4c4b-9924-a51728a42237f">
<img width="400" alt="morebybaye" src="https://github.com/waylybaye/opencat.app/assets/54651817/f9006a98-4a27-402c-913b-439f9e0caa41">
</details>

### Before
<img src="https://github.com/waylybaye/opencat.app/assets/54651817/fd9ed8d9-c396-4e93-81cf-d9b637985f03" alt="before" width="400" />

## Major changes
Add navigation menu, `Screenshots`, `Features` & `More by Baye` sections, `Smart App Banners`. 
Fix issue in dark mode and layout.
Adjust some style, remove unused code and garish decoration.

## Details
### Feat
- add `Smart App Banners` - 5863f8adde15b157349ea090d54e3632d2f17afa 5a2bb3ad821cb9d707cc2ccd4a397aab5b753f55 b0129af66915762f4424e4f848a458cbe13af0d0
- add `Header` component
  - add Theme Toggle - 8065f677713799d1dec9008f91892642786b0b4d
  - add Navigation menu - 1ea8ffd270df5a32606a9daf085ea5bddca6e765
  - add Logo
- add `Footer` component - 8cdd77d31d35b70b489fcd376f806f47697de190
- add Screenshots section - a0ce0309f9507102025130c18a2e69715ca13289
- add More by Baye section - 44bccdb9cf27463a8de41c2f5eb05c69c2b76803
- add Features section - 2a785d73b45200f73d2e9de8040ae9756451e2c1

### Fix
- fix some issue in dark mode - 609618dabc23d935a559cd762869b86f6c91dc6f da17c34faeec071f4a5660ca15e90548ce4ca04e 514bec111d0401f9a109e8e75f7f68873e7eb99b 6e76229179fcdf8063ea5bc16989cc210e01c98f 276dac1783d399ff8b52beafd5dfb2af89ff5e5d
- fix some issue in layout - 971389c963ea40347faece17aff5f306b4806545

### Build
- update dependencies - 00a17496f41077ba7db13a46bef67290da2e43f7 7e0076135a1e738495b2fbbbf9fa91232a9ae699

### Misc
- add required version description - #26 
- etc.
