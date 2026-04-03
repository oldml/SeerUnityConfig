[Compare](https://github.com/oldml/SeerUnityConfig/compare/d9110873464b855ac72d4e6986fe3d5e709b9398...main)

![ConfigPackage](https://img.shields.io/badge/ConfigPackage-20260403003321-blue?style=flat-square)
![DefaultPackage](https://img.shields.io/badge/DefaultPackage-20260402232801-brightgreen?style=flat-square)

> Generated at `2026-04-03 11:00:57 UTC+8` | Branch `main` | Base Commit `d911087`

```diff
! 70 files changed
+ 13,793 insertions(+)
- 1,024 deletions(-)
```

### Created
| Path | Diff (+/-) |
| :--- | :--- |
|  [puchuStageInfoConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/puchuStageInfoConfig.json) | `1,884+` |

### Updated
| Path | Diff (+/-) |
| :--- | :--- |
|  [story_1022.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/story_1022.json) | `6,281+` |
|  [moves.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/moves.json) | `1,063+` |
|  [bossInfo.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/bossInfo.json) | `522+ 508-` |
|  [monsters.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/monsters.json) | `729+` |
|  [Activity_TaskConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Activity_TaskConfig.json) | `272+ 144-` |
|  [autocardContent.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardContent.json) | `161+ 161-` |
|  [product_diamond.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/product_diamond.json) | `270+` |
|  [new_super_design.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/new_super_design.json) | `242+` |
|  [new_monster_level.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/new_monster_level.json) | `227+ 6-` |
|  [ActivityCenter.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/ActivityCenter.json) | `187+ 17-` |
|  [midleItems.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/midleItems.json) | `162+` |
|  [redbadge.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/redbadge.json) | `107+ 9-` |
|  [effectIcon.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectIcon.json) | `104+ 1-` |
|  [buff.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/buff.json) | `101+ 3-` |
|  [petbook.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/petbook.json) | `52+ 33-` |
|  [chapterpoint.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/chapterpoint.json) | `73+ 4-` |
|  [skill_effect.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/skill_effect.json) | `75+` |
|  [mintmark.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/mintmark.json) | `74+` |
|  [LightAndAarkPrizeDraw.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/LightAndAarkPrizeDraw.json) | `72+` |
|  [LightAndAarkDeities.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/LightAndAarkDeities.json) | `72+` |
|  [itemsOptimizeCatItems17.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems17.json) | `69+` |
|  [achievements.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/achievements.json) | `67+ 2-` |
|  [itemsOptimizeCatItems13.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems13.json) | `64+` |
|  [itemsOptimizeCatItems3.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems3.json) | `60+` |
|  [guidePetRecommend.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/guidePetRecommend.json) | `54+` |
|  [effectDes.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectDes.json) | `47+ 7-` |
|  [signIcon_fight.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/signIcon_fight.json) | `52+ 1-` |
|  [equip.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/equip.json) | `52+` |
|  [module.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/module.json) | `49+` |
|  [effectInfo.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectInfo.json) | `46+ 1-` |
|  [pvp_vote.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pvp_vote.json) | `22+ 22-` |
|  [Fragment.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Fragment.json) | `42+` |
|  [jumptarget.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/jumptarget.json) | `37+ 2-` |
|  [vip_pet_shop.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/vip_pet_shop.json) | `19+ 19-` |
|  [LimitedAdastraActivityReward.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/LimitedAdastraActivityReward.json) | `18+ 18-` |
|  [achievementbonus.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/achievementbonus.json) | `32+` |
|  [itemsOptimizeCatItems24.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems24.json) | `30+` |
|  [map.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/map.json) | `26+ 3-` |
|  [archivesStory.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/archivesStory.json) | `24+ 2-` |
|  [autocardBuff.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardBuff.json) | `17+ 8-` |
|  [hide_moves.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/hide_moves.json) | `24+` |
|  [talk.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/talk.json) | `11+ 11-` |
|  [exchange_clt.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/exchange_clt.json) | `22+` |
|  [autocardRole.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardRole.json) | `10+ 10-` |
|  [pet_skin.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pet_skin.json) | `18+` |
|  [chapterreward.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/chapterreward.json) | `16+` |
|  [pet_item.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pet_item.json) | `15+` |
|  [autocardScreen.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardScreen.json) | `12+ 2-` |
|  [suit.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/suit.json) | `13+` |
|  [itemsTip.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsTip.json) | `12+` |
|  [autoOpenPanel.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autoOpenPanel.json) | `12+` |
|  [AdAstraGalaxy.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/AdAstraGalaxy.json) | `6+ 6-` |
|  [open_time_limit.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/open_time_limit.json) | `10+` |
|  [npc.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/npc.json) | `10+` |
|  [autocardSkin.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardSkin.json) | `5+ 5-` |
|  [itemType.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemType.json) | `9+` |
|  [open_bonus.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/open_bonus.json) | `8+` |
|  [monthpet.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/monthpet.json) | `4+ 4-` |
|  [vip_month_monster.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/vip_month_monster.json) | `3+ 3-` |
|  [partnerEffectUpgrade.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/partnerEffectUpgrade.json) | `2+ 2-` |
|  [activityTimeControl.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/activityTimeControl.json) | `2+ 2-` |
|  [achievements_temp.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/achievements_temp.json) | `2+ 2-` |
|  [achievement_rule.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/achievement_rule.json) | `4+` |
|  [storymodel.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/storymodel.json) | `1+ 1-` |
|  [petbook_temp.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/petbook_temp.json) | `1+ 1-` |
|  [pet_skin_temp.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pet_skin_temp.json) | `1+ 1-` |
|  [help_tips.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/help_tips.json) | `1+ 1-` |
|  [dailytask.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/dailytask.json) | `1+ 1-` |
|  [AdAstraLevel.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/AdAstraLevel.json) | `1+ 1-` |

### Removed
| Path | Diff (+/-) |
| :--- | :--- |
|  - | `0` |

