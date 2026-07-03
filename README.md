[Compare](https://github.com/oldml/SeerUnityConfig/compare/5ca7ce7973bd0e2c604c5a0f78a2a5db57a99377...main)

![ConfigPackage](https://img.shields.io/badge/ConfigPackage-20260702212226-blue?style=flat-square)
![DefaultPackage](https://img.shields.io/badge/DefaultPackage-20260702204927-brightgreen?style=flat-square)

> Generated at `2026-07-03 11:10:54 UTC+8` | Branch `main` | Base Commit `5ca7ce7`

```diff
! 49 files changed
+ 18,152 insertions(+)
- 620 deletions(-)
```

### Created
| Path | Diff (+/-) |
| :--- | :--- |
|  [AbyssFisheryLevel.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/AbyssFisheryLevel.json) | `5,604+` |
|  [AbyssFishery.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/AbyssFishery.json) | `404+` |
|  [AbyssFisheryShop.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/AbyssFisheryShop.json) | `154+` |

### Updated
| Path | Diff (+/-) |
| :--- | :--- |
|  [story_1025.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/story_1025.json) | `8,360+` |
|  [peakJihadYearlyRank.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/peakJihadYearlyRank.json) | `345+ 177-` |
|  [gems.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/gems.json) | `495+` |
|  [moves.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/moves.json) | `323+` |
|  [itemsOptimizeCatItems18.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems18.json) | `300+` |
|  [monsters.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/monsters.json) | `284+` |
|  [new_super_design.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/new_super_design.json) | `233+` |
|  [new_monster_level.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/new_monster_level.json) | `209+ 11-` |
|  [autocardContent.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardContent.json) | `64+ 112-` |
|  [product_diamond.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/product_diamond.json) | `172+ 2-` |
|  [ActivityCenter.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/ActivityCenter.json) | `124+ 39-` |
|  [effectInfo.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectInfo.json) | `159+` |
|  [redbadge.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/redbadge.json) | `110+ 11-` |
|  [pet_skin.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pet_skin.json) | `56+ 56-` |
|  [midleItems.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/midleItems.json) | `104+ 2-` |
|  [JackPotShop.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/JackPotShop.json) | `9+ 84-` |
|  [chapterpoint.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/chapterpoint.json) | `92+` |
|  [storymodel.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/storymodel.json) | `67+ 1-` |
|  [petbook.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/petbook.json) | `33+ 32-` |
|  [guidePetRecommend.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/guidePetRecommend.json) | `54+` |
|  [effectIcon.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectIcon.json) | `50+` |
|  [module.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/module.json) | `49+` |
|  [pvp_vote.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pvp_vote.json) | `22+ 22-` |
|  [itemsOptimizeCatItems17.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems17.json) | `33+ 10-` |
|  [dayDreamStoryConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/dayDreamStoryConfig.json) | `19+ 19-` |
|  [autocardBuff.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardBuff.json) | `25+ 7-` |
|  [archivesStory.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/archivesStory.json) | `27+ 5-` |
|  [buff.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/buff.json) | `30+` |
|  [map.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/map.json) | `23+ 2-` |
|  [autocardRole.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardRole.json) | `12+ 12-` |
|  [help_tips.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/help_tips.json) | `18+ 2-` |
|  [jumptarget.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/jumptarget.json) | `14+` |
|  [Fragment.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Fragment.json) | `14+` |
|  [hide_moves.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/hide_moves.json) | `12+` |
|  [itemsOptimizeCatItems24.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems24.json) | `10+` |
|  [open_bonus.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/open_bonus.json) | `8+` |
|  [monthpet.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/monthpet.json) | `4+ 4-` |
|  [chapterreward.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/chapterreward.json) | `8+` |
|  [vip_month_monster.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/vip_month_monster.json) | `3+ 3-` |
|  [autocardSeasonEffect.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardSeasonEffect.json) | `3+ 3-` |
|  [open_time_limit.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/open_time_limit.json) | `5+` |
|  [itemsTip.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsTip.json) | `4+` |
|  [petEffectIcon.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/petEffectIcon.json) | `1+ 1-` |
|  [npc.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/npc.json) | `1+ 1-` |
|  [autoOpenPanel.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autoOpenPanel.json) | `1+ 1-` |
|  [active_sort.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/active_sort.json) | `1+ 1-` |

### Removed
| Path | Diff (+/-) |
| :--- | :--- |
|  - | `0` |

