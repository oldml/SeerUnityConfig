[Compare](https://github.com/oldml/SeerUnityConfig/compare/23ebd8e2d668b119fa8086ca134a8189e78aa70e...main)

![ConfigPackage](https://img.shields.io/badge/ConfigPackage-20260515000652-blue?style=flat-square)
![DefaultPackage](https://img.shields.io/badge/DefaultPackage-20260515110440-brightgreen?style=flat-square)

> Generated at `2026-05-15 12:00:58 UTC+8` | Branch `main` | Base Commit `23ebd8e`

```diff
! 64 files changed
+ 23,240 insertions(+)
- 860 deletions(-)
```

### Created
| Path | Diff (+/-) |
| :--- | :--- |
|  [story_1017.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/story_1017.json) | `7,627+` |
|  [story_1024.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/story_1024.json) | `6,472+` |
|  [story_1014.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/story_1014.json) | `2,358+` |
|  [aurumEndgameEnemyConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/aurumEndgameEnemyConfig.json) | `407+` |
|  [aurumEndgameStageConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/aurumEndgameStageConfig.json) | `376+` |
|  [aurumEndgameExpConfig_endless.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/aurumEndgameExpConfig_endless.json) | `254+` |
|  [aurumEndgameExpConfig_adven.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/aurumEndgameExpConfig_adven.json) | `254+` |
|  [aurumEndgameShop.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/aurumEndgameShop.json) | `58+` |
|  [aurumEndgameTutorialConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/aurumEndgameTutorialConfig.json) | `53+` |
|  [storyAnniversary2026SideQuests.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/storyAnniversary2026SideQuests.json) | `44+` |
|  [storyAnniversary2026Items.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/storyAnniversary2026Items.json) | `32+` |
|  [storyAnniversary2026Main.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/storyAnniversary2026Main.json) | `31+` |
|  [autocardScene.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardScene.json) | `20+` |

### Updated
| Path | Diff (+/-) |
| :--- | :--- |
|  [treasure_chest_gift.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/treasure_chest_gift.json) | `1,280+ 234-` |
|  [aurumEndgameOptionsConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/aurumEndgameOptionsConfig.json) | `447+ 303-` |
|  [Activity_ShopConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Activity_ShopConfig.json) | `480+` |
|  [monsters.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/monsters.json) | `398+` |
|  [moves.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/moves.json) | `335+` |
|  [Attirerecycle.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Attirerecycle.json) | `300+` |
|  [new_super_design.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/new_super_design.json) | `242+` |
|  [story_1023.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/story_1023.json) | `103+ 92-` |
|  [itemsOptimizeCatItems26.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems26.json) | `132+` |
|  [ActivityCenter.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/ActivityCenter.json) | `107+ 22-` |
|  [redbadge.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/redbadge.json) | `118+ 5-` |
|  [product_diamond.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/product_diamond.json) | `111+ 1-` |
|  [chapterpoint.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/chapterpoint.json) | `94+ 2-` |
|  [guidePetRecommend.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/guidePetRecommend.json) | `81+` |
|  [autocardContent.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardContent.json) | `39+ 39-` |
|  [autocardRole.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardRole.json) | `38+ 38-` |
|  [pet_skin.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pet_skin.json) | `54+ 18-` |
|  [new_monster_level.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/new_monster_level.json) | `63+ 5-` |
|  [midleItems.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/midleItems.json) | `67+ 1-` |
|  [buff.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/buff.json) | `64+` |
|  [module.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/module.json) | `59+ 3-` |
|  [pvp_ban.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pvp_ban.json) | `28+ 31-` |
|  [petbook.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/petbook.json) | `50+ 5-` |
|  [itemsTip.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsTip.json) | `52+` |
|  [effectIcon.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectIcon.json) | `52+` |
|  [storymodel.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/storymodel.json) | `46+ 2-` |
|  [newer_guide_h5_2.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/newer_guide_h5_2.json) | `48+` |
|  [effectInfo.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectInfo.json) | `41+ 4-` |
|  [mintmark.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/mintmark.json) | `38+` |
|  [awakenlist.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/awakenlist.json) | `36+` |
|  [autocardBuff.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardBuff.json) | `31+ 4-` |
|  [skill_effect.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/skill_effect.json) | `30+` |
|  [jumptarget.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/jumptarget.json) | `28+` |
|  [help_tips.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/help_tips.json) | `24+` |
|  [chapter.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/chapter.json) | `12+ 12-` |
|  [archivesStory.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/archivesStory.json) | `16+ 5-` |
|  [achievements.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/achievements.json) | `16+ 2-` |
|  [rebate.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/rebate.json) | `5+ 11-` |
|  [battle_effects.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/battle_effects.json) | `15+` |
|  [newBraveLv.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/newBraveLv.json) | `7+ 7-` |
|  [Fragment.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Fragment.json) | `14+` |
|  [hide_moves.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/hide_moves.json) | `13+` |
|  [itemsOptimizeCatItems24.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems24.json) | `10+` |
|  [newer_guide_h5.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/newer_guide_h5.json) | `4+ 4-` |
|  [chapterreward.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/chapterreward.json) | `8+` |
|  [achievementbonus.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/achievementbonus.json) | `8+` |
|  [active_sort.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/active_sort.json) | `3+ 3-` |
|  [pvp_vote.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pvp_vote.json) | `2+ 2-` |
|  [pvp_ban_expert.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pvp_ban_expert.json) | `2+ 2-` |
|  [effectDes.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectDes.json) | `2+ 2-` |
|  [autoOpenPanel.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autoOpenPanel.json) | `1+ 1-` |

### Removed
| Path | Diff (+/-) |
| :--- | :--- |
|  - | `0` |

