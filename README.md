[Compare](https://github.com/oldml/SeerUnityConfig/compare/39d1cbcd93182a311c551e2fc12a6bf8cf23a383...main)

![ConfigPackage](https://img.shields.io/badge/ConfigPackage-20260305213111-blue?style=flat-square)
![DefaultPackage](https://img.shields.io/badge/DefaultPackage-20260305222201-brightgreen?style=flat-square)

> Generated at `2026-03-06 11:11:05 UTC+8` | Branch `main` | Base Commit `39d1cbc`

```diff
! 54 files changed
+ 13,278 insertions(+)
- 1,548 deletions(-)
```

### Created
| Path | Diff (+/-) |
| :--- | :--- |
|  [story_1015.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/story_1015.json) | `5,658+` |
|  [newSetGame.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/newSetGame.json) | `1,408+` |
|  [clickfps_game.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/clickfps_game.json) | `154+` |
|  [elfGachaStore.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/elfGachaStore.json) | `92+` |

### Updated
| Path | Diff (+/-) |
| :--- | :--- |
|  [bagTower_StageFight.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/bagTower_StageFight.json) | `680+ 680-` |
|  [bossInfo.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/bossInfo.json) | `544+ 544-` |
|  [talk.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/talk.json) | `581+ 101-` |
|  [battle_effects.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/battle_effects.json) | `517+ 47-` |
|  [monsters.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/monsters.json) | `486+` |
|  [moves.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/moves.json) | `441+ 2-` |
|  [new_monster_level.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/new_monster_level.json) | `380+ 31-` |
|  [Activity_TaskConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Activity_TaskConfig.json) | `272+` |
|  [new_super_design.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/new_super_design.json) | `233+` |
|  [ActivityCenter.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/ActivityCenter.json) | `191+ 21-` |
|  [product_diamond.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/product_diamond.json) | `200+` |
|  [redbadge.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/redbadge.json) | `193+ 4-` |
|  [midleItems.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/midleItems.json) | `120+` |
|  [chapterpoint.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/chapterpoint.json) | `115+` |
|  [effectIcon.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectIcon.json) | `83+ 5-` |
|  [guidePetRecommend.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/guidePetRecommend.json) | `81+` |
|  [module.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/module.json) | `70+` |
|  [itemsOptimizeCatItems17.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems17.json) | `69+` |
|  [storymodel.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/storymodel.json) | `66+` |
|  [jumptarget.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/jumptarget.json) | `57+ 1-` |
|  [awakenlist.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/awakenlist.json) | `54+` |
|  [buff.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/buff.json) | `49+ 1-` |
|  [petbook.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/petbook.json) | `33+ 15-` |
|  [Fragment.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Fragment.json) | `42+` |
|  [sp_hide_moves.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/sp_hide_moves.json) | `40+` |
|  [pvp_vote.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pvp_vote.json) | `19+ 19-` |
|  [pet_skin.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pet_skin.json) | `36+` |
|  [LimitedAdastraActivityReward.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/LimitedAdastraActivityReward.json) | `18+ 18-` |
|  [chapterreward.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/chapterreward.json) | `32+` |
|  [map.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/map.json) | `26+ 5-` |
|  [itemsOptimizeCatItems24.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems24.json) | `30+` |
|  [itemsTip.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsTip.json) | `28+` |
|  [archivesStory.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/archivesStory.json) | `25+ 3-` |
|  [exchange_clt.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/exchange_clt.json) | `22+` |
|  [chapter.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/chapter.json) | `11+ 11-` |
|  [npc.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/npc.json) | `20+` |
|  [effectInfo.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectInfo.json) | `10+ 10-` |
|  [hide_moves.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/hide_moves.json) | `18+` |
|  [itemsOptimizeCatItems14.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems14.json) | `12+` |
|  [help_tips.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/help_tips.json) | `10+ 2-` |
|  [AdAstraLevel.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/AdAstraLevel.json) | `6+ 6-` |
|  [AdAstraGalaxy.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/AdAstraGalaxy.json) | `6+ 6-` |
|  [classicSweepInfo.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/classicSweepInfo.json) | `11+` |
|  [open_bonus.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/open_bonus.json) | `8+` |
|  [monthpet.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/monthpet.json) | `4+ 4-` |
|  [vip_month_monster.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/vip_month_monster.json) | `3+ 3-` |
|  [starmap.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/starmap.json) | `3+ 3-` |
|  [effectDes.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectDes.json) | `3+ 3-` |
|  [active_sort.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/active_sort.json) | `3+ 3-` |
|  [open_time_limit.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/open_time_limit.json) | `5+` |

### Removed
| Path | Diff (+/-) |
| :--- | :--- |
|  - | `0` |

