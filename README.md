[Compare](https://github.com/oldml/SeerUnityConfig/compare/ba4beb65f23d025e6538e6c4cb41ec465f443855...main)

![ConfigPackage](https://img.shields.io/badge/ConfigPackage-20260730210447-blue?style=flat-square)
![DefaultPackage](https://img.shields.io/badge/DefaultPackage-20260730210405-brightgreen?style=flat-square)

> Generated at `2026-07-31 11:01:18 UTC+8` | Branch `main` | Base Commit `ba4beb6`

```diff
! 53 files changed
+ 7,987 insertions(+)
- 24,230 deletions(-)
```

### Created
| Path | Diff (+/-) |
| :--- | :--- |
|  - | `0` |

### Updated
| Path | Diff (+/-) |
| :--- | :--- |
|  [product_diamond.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/product_diamond.json) | `63+ 24,005-` |
|  [story_1026.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/story_1026.json) | `5,347+ 1-` |
|  [moves.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/moves.json) | `311+` |
|  [monsters.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/monsters.json) | `284+` |
|  [new_super_design.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/new_super_design.json) | `233+` |
|  [redbadge.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/redbadge.json) | `223+ 4-` |
|  [new_monster_level.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/new_monster_level.json) | `126+ 8-` |
|  [ActivityCenter.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/ActivityCenter.json) | `126+ 7-` |
|  [autocardBuff.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardBuff.json) | `110+ 2-` |
|  [talk.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/talk.json) | `99+ 9-` |
|  [autocardRole.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardRole.json) | `100+` |
|  [autocardContent.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardContent.json) | `71+ 23-` |
|  [pet_skin_reward.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pet_skin_reward.json) | `78+` |
|  [chapterpoint.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/chapterpoint.json) | `71+ 2-` |
|  [pet_skin_rewardtype.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pet_skin_rewardtype.json) | `46+ 22-` |
|  [signIcon_fight.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/signIcon_fight.json) | `64+` |
|  [effectIcon.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectIcon.json) | `53+ 3-` |
|  [guidePetRecommend.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/guidePetRecommend.json) | `54+` |
|  [pet_skin.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pet_skin.json) | `26+ 26-` |
|  [midleItems.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/midleItems.json) | `48+` |
|  [petbook.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/petbook.json) | `17+ 27-` |
|  [autocardPlayer.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardPlayer.json) | `42+` |
|  [storymodel.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/storymodel.json) | `37+ 4-` |
|  [profilephoto.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/profilephoto.json) | `37+ 3-` |
|  [autocardSeasonEffect.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardSeasonEffect.json) | `20+ 20-` |
|  [pvp_vote.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pvp_vote.json) | `19+ 19-` |
|  [archivesStory.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/archivesStory.json) | `29+ 3-` |
|  [buff.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/buff.json) | `29+ 1-` |
|  [jumptarget.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/jumptarget.json) | `25+ 4-` |
|  [skinMon.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/skinMon.json) | `27+` |
|  [module.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/module.json) | `21+` |
|  [achievements.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/achievements.json) | `16+ 2-` |
|  [autocardSkin.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardSkin.json) | `16+` |
|  [Fragment.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Fragment.json) | `14+` |
|  [hide_moves.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/hide_moves.json) | `12+` |
|  [Activity_TimeUpdateConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Activity_TimeUpdateConfig.json) | `11+` |
|  [product_money.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/product_money.json) | `10+` |
|  [itemsOptimizeCatItems24.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems24.json) | `10+` |
|  [autocardbattlepass_reward.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardbattlepass_reward.json) | `5+ 5-` |
|  [autocardScreen.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardScreen.json) | `0+ 10-` |
|  [open_bonus.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/open_bonus.json) | `8+` |
|  [monthpet.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/monthpet.json) | `4+ 4-` |
|  [itemsTip.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsTip.json) | `8+` |
|  [effectDes.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectDes.json) | `4+ 4-` |
|  [chapterreward.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/chapterreward.json) | `8+` |
|  [autocardbattlepass_task.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardbattlepass_task.json) | `4+ 4-` |
|  [achievementbonus.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/achievementbonus.json) | `8+` |
|  [vip_month_monster.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/vip_month_monster.json) | `3+ 3-` |
|  [open_time_limit.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/open_time_limit.json) | `5+` |
|  [effectInfo.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectInfo.json) | `2+ 2-` |
|  [npc.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/npc.json) | `1+ 1-` |
|  [itemsOptimizeCatItems17.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems17.json) | `1+ 1-` |
|  [help_tips.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/help_tips.json) | `1+ 1-` |

### Removed
| Path | Diff (+/-) |
| :--- | :--- |
|  - | `0` |

