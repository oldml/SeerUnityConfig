[Compare](https://github.com/oldml/SeerUnityConfig/compare/26d965af7e997efb37816e99090d021af4d78db3...main)

![ConfigPackage](https://img.shields.io/badge/ConfigPackage-20260313104016-blue?style=flat-square)
![DefaultPackage](https://img.shields.io/badge/DefaultPackage-20260313000359-brightgreen?style=flat-square)

> Generated at `2026-03-13 11:41:23 UTC+8` | Branch `main` | Base Commit `26d965a`

```diff
! 44 files changed
+ 8,009 insertions(+)
- 187 deletions(-)
```

### Created
| Path | Diff (+/-) |
| :--- | :--- |
|  [petclassfix.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/petclassfix.json) | `25+` |

### Updated
| Path | Diff (+/-) |
| :--- | :--- |
|  [story_1015.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/story_1015.json) | `4,797+ 1-` |
|  [monsters.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/monsters.json) | `476+ 1-` |
|  [moves.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/moves.json) | `411+` |
|  [new_super_design.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/new_super_design.json) | `233+` |
|  [redbadge.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/redbadge.json) | `227+ 4-` |
|  [ActivityCenter.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/ActivityCenter.json) | `196+ 9-` |
|  [Activity_TaskConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Activity_TaskConfig.json) | `140+ 44-` |
|  [product_diamond.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/product_diamond.json) | `180+` |
|  [talk.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/talk.json) | `153+` |
|  [JackPotShop.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/JackPotShop.json) | `144+ 9-` |
|  [pet_skin.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pet_skin.json) | `83+ 47-` |
|  [midleItems.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/midleItems.json) | `108+` |
|  [chapterpoint.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/chapterpoint.json) | `98+ 6-` |
|  [new_monster_level.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/new_monster_level.json) | `82+ 2-` |
|  [Unbindmintinfo.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Unbindmintinfo.json) | `76+` |
|  [pet_skin_reward.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pet_skin_reward.json) | `66+` |
|  [effectIcon.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectIcon.json) | `54+ 2-` |
|  [petbook.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/petbook.json) | `30+ 12-` |
|  [mintmark.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/mintmark.json) | `39+ 1-` |
|  [module.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/module.json) | `35+` |
|  [profilephoto.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/profilephoto.json) | `34+` |
|  [achievements.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/achievements.json) | `30+ 2-` |
|  [map.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/map.json) | `27+ 4-` |
|  [help_tips.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/help_tips.json) | `19+ 11-` |
|  [guidePetRecommend.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/guidePetRecommend.json) | `27+` |
|  [map_config.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/map_config.json) | `26+` |
|  [pet_skin_rewardtype.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pet_skin_rewardtype.json) | `24+` |
|  [dailytask_gift.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/dailytask_gift.json) | `12+ 12-` |
|  [itemsOptimizeCatItems17.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems17.json) | `23+` |
|  [jumptarget.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/jumptarget.json) | `21+` |
|  [archivesStory.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/archivesStory.json) | `14+ 3-` |
|  [rebate.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/rebate.json) | `5+ 11-` |
|  [achievementbonus.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/achievementbonus.json) | `16+` |
|  [Fragment.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Fragment.json) | `14+` |
|  [hide_moves.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/hide_moves.json) | `12+` |
|  [effectDes.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectDes.json) | `11+ 1-` |
|  [buff.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/buff.json) | `11+ 1-` |
|  [storymodel.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/storymodel.json) | `11+` |
|  [itemsOptimizeCatItems24.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems24.json) | `10+` |
|  [pvp_vote.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pvp_vote.json) | `2+ 2-` |
|  [itemsTip.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsTip.json) | `4+` |
|  [starmap.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/starmap.json) | `2+ 1-` |
|  [effectInfo.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectInfo.json) | `1+ 1-` |

### Removed
| Path | Diff (+/-) |
| :--- | :--- |
|  - | `0` |

