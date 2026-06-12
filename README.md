[Compare](https://github.com/oldml/SeerUnityConfig/compare/fe21b9433dd27d3b72ed4b931a3755edfe63fada...main)

![ConfigPackage](https://img.shields.io/badge/ConfigPackage-20260611221428-blue?style=flat-square)
![DefaultPackage](https://img.shields.io/badge/DefaultPackage-20260611233633-brightgreen?style=flat-square)

> Generated at `2026-06-12 11:40:44 UTC+8` | Branch `main` | Base Commit `fe21b94`

```diff
! 62 files changed
+ 14,995 insertions(+)
- 428 deletions(-)
```

### Created
| Path | Diff (+/-) |
| :--- | :--- |
|  [mysteryBoxGameItem.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/mysteryBoxGameItem.json) | `544+` |
|  [mysteryBoxGameSkill.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/mysteryBoxGameSkill.json) | `137+` |
|  [mysteryBoxGameLevel.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/mysteryBoxGameLevel.json) | `104+` |
|  [skinStoregacha.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/skinStoregacha.json) | `44+` |

### Updated
| Path | Diff (+/-) |
| :--- | :--- |
|  [story_1017.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/story_1017.json) | `8,811+` |
|  [monsters.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/monsters.json) | `1,089+` |
|  [talk.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/talk.json) | `856+ 109-` |
|  [moves.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/moves.json) | `409+` |
|  [redbadge.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/redbadge.json) | `381+ 5-` |
|  [Unbindmintinfo.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Unbindmintinfo.json) | `344+` |
|  [mintmark.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/mintmark.json) | `334+ 8-` |
|  [product_diamond.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/product_diamond.json) | `196+ 6-` |
|  [ActivityCenter.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/ActivityCenter.json) | `163+ 27-` |
|  [new_monster_level.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/new_monster_level.json) | `108+ 28-` |
|  [midleItems.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/midleItems.json) | `121+ 7-` |
|  [chapterpoint.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/chapterpoint.json) | `120+ 5-` |
|  [Activity_TaskConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Activity_TaskConfig.json) | `112+` |
|  [pet_skin.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pet_skin.json) | `94+ 4-` |
|  [petbook.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/petbook.json) | `39+ 54-` |
|  [storyAnniversary2026FreeShop.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/storyAnniversary2026FreeShop.json) | `90+` |
|  [signIcon_fight.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/signIcon_fight.json) | `80+` |
|  [itemsOptimizeCatItems17.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems17.json) | `59+ 13-` |
|  [elfGachaReward.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/elfGachaReward.json) | `33+ 33-` |
|  [itemsOptimizeCatItems13.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems13.json) | `64+` |
|  [aurumEndgameOptionsConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/aurumEndgameOptionsConfig.json) | `32+ 32-` |
|  [jumptarget.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/jumptarget.json) | `63+` |
|  [storyAnniversary2026Main.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/storyAnniversary2026Main.json) | `54+` |
|  [equip.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/equip.json) | `52+` |
|  [module.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/module.json) | `49+` |
|  [buff.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/buff.json) | `40+` |
|  [vip_pet_shop.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/vip_pet_shop.json) | `18+ 18-` |
|  [elfGachaTask.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/elfGachaTask.json) | `18+ 18-` |
|  [achievements.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/achievements.json) | `31+ 3-` |
|  [itemsTip.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsTip.json) | `28+` |
|  [effectDes.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectDes.json) | `24+ 4-` |
|  [aurumEndgameStageConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/aurumEndgameStageConfig.json) | `14+ 14-` |
|  [guidePetRecommend.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/guidePetRecommend.json) | `27+` |
|  [effectIcon.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectIcon.json) | `26+` |
|  [storymodel.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/storymodel.json) | `23+ 1-` |
|  [npc.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/npc.json) | `20+` |
|  [help_tips.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/help_tips.json) | `18+ 2-` |
|  [archivesStory.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/archivesStory.json) | `15+ 4-` |
|  [rebate.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/rebate.json) | `5+ 11-` |
|  [skill_effect.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/skill_effect.json) | `15+` |
|  [battle_effects.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/battle_effects.json) | `15+` |
|  [suit.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/suit.json) | `13+` |
|  [new_super_design.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/new_super_design.json) | `6+ 6-` |
|  [effectInfo.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectInfo.json) | `10+ 1-` |
|  [skillTypes.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/skillTypes.json) | `10+` |
|  [achievementbonus.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/achievementbonus.json) | `8+` |
|  [hide_moves.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/hide_moves.json) | `6+` |
|  [open_time_limit.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/open_time_limit.json) | `5+` |
|  [pvp_vote.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pvp_vote.json) | `2+ 2-` |
|  [map.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/map.json) | `2+ 2-` |
|  [elfGacha.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/elfGacha.json) | `2+ 2-` |
|  [aurumEndgameEnemyConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/aurumEndgameEnemyConfig.json) | `2+ 2-` |
|  [activityTimeControl.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/activityTimeControl.json) | `2+ 2-` |
|  [active_sort.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/active_sort.json) | `3+ 1-` |
|  [starmap.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/starmap.json) | `2+ 1-` |
|  [storyAnniversary2026Items.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/storyAnniversary2026Items.json) | `1+ 1-` |
|  [starrySkyStoryConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/starrySkyStoryConfig.json) | `1+ 1-` |
|  [Activity_ShopConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Activity_ShopConfig.json) | `1+ 1-` |

### Removed
| Path | Diff (+/-) |
| :--- | :--- |
|  - | `0` |

