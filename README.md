[Compare](https://github.com/oldml/SeerUnityConfig/compare/89952b81fa373bb0d12bfe7b25c8e2ba55ae8ffb...main)

![ConfigPackage](https://img.shields.io/badge/ConfigPackage-20260430003951-blue?style=flat-square)
![DefaultPackage](https://img.shields.io/badge/DefaultPackage-20260429233341-brightgreen?style=flat-square)

> Generated at `2026-04-30 12:01:02 UTC+8` | Branch `main` | Base Commit `89952b8`

```diff
! 61 files changed
+ 23,295 insertions(+)
- 1,307 deletions(-)
```

### Created
| Path | Diff (+/-) |
| :--- | :--- |
|  [aurumEndgameOptionsConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/aurumEndgameOptionsConfig.json) | `940+` |
|  [zumaGme.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/zumaGme.json) | `365+` |

### Updated
| Path | Diff (+/-) |
| :--- | :--- |
|  [story_1023.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/story_1023.json) | `15,599+ 1-` |
|  [autocardContent.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardContent.json) | `1,948+ 940-` |
|  [monsters.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/monsters.json) | `664+` |
|  [moves.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/moves.json) | `640+` |
|  [talk.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/talk.json) | `237+ 51-` |
|  [autocardRole.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardRole.json) | `225+ 5-` |
|  [ActivityCenter.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/ActivityCenter.json) | `215+ 11-` |
|  [redbadge.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/redbadge.json) | `202+ 2-` |
|  [new_monster_level.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/new_monster_level.json) | `155+ 17-` |
|  [bossInfo.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/bossInfo.json) | `80+ 80-` |
|  [product_diamond.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/product_diamond.json) | `122+ 12-` |
|  [autocardBuff.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardBuff.json) | `105+ 15-` |
|  [effectIcon.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectIcon.json) | `109+ 4-` |
|  [boruca_strategy.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/boruca_strategy.json) | `85+ 22-` |
|  [module.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/module.json) | `105+` |
|  [midleItems.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/midleItems.json) | `90+ 12-` |
|  [guidePetRecommend.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/guidePetRecommend.json) | `89+ 8-` |
|  [signIcon_fight.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/signIcon_fight.json) | `93+ 1-` |
|  [effectDes.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectDes.json) | `84+ 4-` |
|  [petbook.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/petbook.json) | `76+ 8-` |
|  [pet_skin.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pet_skin.json) | `59+ 5-` |
|  [chapterpoint.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/chapterpoint.json) | `54+ 8-` |
|  [newer_guide_h5_2.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/newer_guide_h5_2.json) | `60+` |
|  [help_tips.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/help_tips.json) | `57+ 1-` |
|  [effectInfo.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectInfo.json) | `41+ 16-` |
|  [skinMon.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/skinMon.json) | `55+ 1-` |
|  [profilephoto.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/profilephoto.json) | `51+` |
|  [npc.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/npc.json) | `42+ 2-` |
|  [exchange_clt.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/exchange_clt.json) | `44+` |
|  [skill_effect.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/skill_effect.json) | `36+ 6-` |
|  [Fragment.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Fragment.json) | `42+` |
|  [newer_guide_h5.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/newer_guide_h5.json) | `41+` |
|  [itemsTip.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsTip.json) | `40+` |
|  [pvp_vote.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pvp_vote.json) | `19+ 19-` |
|  [mintmark.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/mintmark.json) | `38+` |
|  [LimitedAdastraActivityReward.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/LimitedAdastraActivityReward.json) | `18+ 18-` |
|  [jumptarget.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/jumptarget.json) | `35+` |
|  [itemsOptimizeCatItems17.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems17.json) | `29+ 6-` |
|  [achievements.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/achievements.json) | `31+ 3-` |
|  [archivesStory.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/archivesStory.json) | `27+ 5-` |
|  [itemsOptimizeCatItems24.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems24.json) | `30+` |
|  [pet_skin_reward.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pet_skin_reward.json) | `26+` |
|  [product_money.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/product_money.json) | `22+ 2-` |
|  [hide_moves.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/hide_moves.json) | `24+` |
|  [autoOpenPanel.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autoOpenPanel.json) | `24+` |
|  [buff.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/buff.json) | `21+ 1-` |
|  [map.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/map.json) | `21+` |
|  [chapterreward.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/chapterreward.json) | `18+ 2-` |
|  [achievementbonus.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/achievementbonus.json) | `16+` |
|  [AdAstraGalaxy.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/AdAstraGalaxy.json) | `6+ 6-` |
|  [pet_skin_rewardtype.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pet_skin_rewardtype.json) | `8+` |
|  [open_bonus.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/open_bonus.json) | `8+` |
|  [monthpet.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/monthpet.json) | `4+ 4-` |
|  [vip_month_monster.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/vip_month_monster.json) | `3+ 3-` |
|  [borucashop.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/borucashop.json) | `3+ 3-` |
|  [starmap.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/starmap.json) | `3+ 2-` |
|  [open_time_limit.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/open_time_limit.json) | `5+` |
|  [autocardNature.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardNature.json) | `5+` |
|  [battle_effects.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/battle_effects.json) | `1+ 1-` |

### Removed
| Path | Diff (+/-) |
| :--- | :--- |
|  - | `0` |

