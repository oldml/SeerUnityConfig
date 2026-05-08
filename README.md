[Compare](https://github.com/oldml/SeerUnityConfig/compare/75655febc90926a10d14567ed1ca7d4af6a8e04e...main)

![ConfigPackage](https://img.shields.io/badge/ConfigPackage-20260507220534-blue?style=flat-square)
![DefaultPackage](https://img.shields.io/badge/DefaultPackage-20260507231736-brightgreen?style=flat-square)

> Generated at `2026-05-08 11:10:47 UTC+8` | Branch `main` | Base Commit `75655fe`

```diff
! 39 files changed
+ 9,582 insertions(+)
- 885 deletions(-)
```

### Created
| Path | Diff (+/-) |
| :--- | :--- |
|  - | `0` |

### Updated
| Path | Diff (+/-) |
| :--- | :--- |
|  [story_1023.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/story_1023.json) | `7,216+` |
|  [dangoAction.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/dangoAction.json) | `0+ 484-` |
|  [redbadge.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/redbadge.json) | `335+ 8-` |
|  [suitsale.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/suitsale.json) | `104+ 188-` |
|  [new_super_design.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/new_super_design.json) | `233+` |
|  [new_monster_level.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/new_monster_level.json) | `202+ 6-` |
|  [guidePetRecommend.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/guidePetRecommend.json) | `195+ 6-` |
|  [ActivityCenter.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/ActivityCenter.json) | `146+ 27-` |
|  [moves.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/moves.json) | `151+` |
|  [mintmark_lottery.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/mintmark_lottery.json) | `140+ 5-` |
|  [monsters.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/monsters.json) | `142+` |
|  [Monsterpool.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Monsterpool.json) | `108+` |
|  [product_diamond.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/product_diamond.json) | `100+` |
|  [chapterpoint.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/chapterpoint.json) | `94+ 2-` |
|  [petbook.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/petbook.json) | `14+ 74-` |
|  [midleItems.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/midleItems.json) | `60+` |
|  [jumptarget.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/jumptarget.json) | `49+` |
|  [autocardContent.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardContent.json) | `24+ 24-` |
|  [vip_pet_shop.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/vip_pet_shop.json) | `23+ 23-` |
|  [itemsOptimizeCatItems17.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems17.json) | `46+` |
|  [module.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/module.json) | `35+` |
|  [effectIcon.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectIcon.json) | `26+` |
|  [archivesStory.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/archivesStory.json) | `17+ 6-` |
|  [exchange_clt.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/exchange_clt.json) | `22+` |
|  [buff.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/buff.json) | `16+ 6-` |
|  [zumaGme.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/zumaGme.json) | `9+ 9-` |
|  [chapterreward.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/chapterreward.json) | `11+ 3-` |
|  [Fragment.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Fragment.json) | `14+` |
|  [storymodel.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/storymodel.json) | `11+` |
|  [itemsOptimizeCatItems24.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems24.json) | `10+` |
|  [hide_moves.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/hide_moves.json) | `6+` |
|  [autocardRole.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardRole.json) | `3+ 3-` |
|  [autocardBuff.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardBuff.json) | `3+ 3-` |
|  [open_time_limit.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/open_time_limit.json) | `5+` |
|  [skill_effect.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/skill_effect.json) | `2+ 2-` |
|  [pvp_vote.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pvp_vote.json) | `2+ 2-` |
|  [itemsTip.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsTip.json) | `4+` |
|  [effectDes.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectDes.json) | `2+ 2-` |
|  [activityTimeControl.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/activityTimeControl.json) | `2+ 2-` |

### Removed
| Path | Diff (+/-) |
| :--- | :--- |
|  - | `0` |

