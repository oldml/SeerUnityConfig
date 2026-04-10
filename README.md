[Compare](https://github.com/oldml/SeerUnityConfig/compare/e680e7caac9903cbaddfe6f274e5a68be084dff0...main)

![ConfigPackage](https://img.shields.io/badge/ConfigPackage-20260410103906-blue?style=flat-square)
![DefaultPackage](https://img.shields.io/badge/DefaultPackage-20260409221555-brightgreen?style=flat-square)

> Generated at `2026-04-10 11:10:50 UTC+8` | Branch `main` | Base Commit `e680e7c`

```diff
! 55 files changed
+ 26,636 insertions(+)
- 330 deletions(-)
```

### Created
| Path | Diff (+/-) |
| :--- | :--- |
|  [story_1016.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/story_1016.json) | `8,034+` |
|  [skinStorePool.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/skinStorePool.json) | `6,179+` |
|  [carrygame_stage.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/carrygame_stage.json) | `214+` |
|  [skinMon.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/skinMon.json) | `58+` |
|  [skinStoreTicket.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/skinStoreTicket.json) | `28+` |
|  [peakJihadYearlyRank.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/peakJihadYearlyRank.json) | `10+` |

### Updated
| Path | Diff (+/-) |
| :--- | :--- |
|  [guidePetRecommend.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/guidePetRecommend.json) | `8,856+` |
|  [redbadge.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/redbadge.json) | `383+ 17-` |
|  [moves.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/moves.json) | `313+ 20-` |
|  [talk.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/talk.json) | `287+ 44-` |
|  [monsters.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/monsters.json) | `315+ 1-` |
|  [new_super_design.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/new_super_design.json) | `233+` |
|  [skill_effect.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/skill_effect.json) | `150+` |
|  [ActivityCenter.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/ActivityCenter.json) | `130+ 11-` |
|  [itemsOptimizeCatItems17.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems17.json) | `121+ 6-` |
|  [effectInfo.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectInfo.json) | `110+ 2-` |
|  [product_diamond.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/product_diamond.json) | `105+ 5-` |
|  [chapterpoint.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/chapterpoint.json) | `98+ 6-` |
|  [storymodel.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/storymodel.json) | `89+ 1-` |
|  [effectIcon.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectIcon.json) | `83+ 6-` |
|  [midleItems.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/midleItems.json) | `77+ 5-` |
|  [partner.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/partner.json) | `47+ 34-` |
|  [new_monster_level.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/new_monster_level.json) | `66+ 10-` |
|  [shop_config.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/shop_config.json) | `72+` |
|  [signIcon_fight.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/signIcon_fight.json) | `65+ 1-` |
|  [petbook.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/petbook.json) | `20+ 41-` |
|  [pet_skin.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pet_skin.json) | `39+ 21-` |
|  [map.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/map.json) | `29+ 26-` |
|  [buff.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/buff.json) | `40+` |
|  [effectDes.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectDes.json) | `32+ 2-` |
|  [itemsTip.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsTip.json) | `32+` |
|  [help_tips.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/help_tips.json) | `32+` |
|  [module.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/module.json) | `29+ 1-` |
|  [shop_attire.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/shop_attire.json) | `29+` |
|  [autocardContent.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardContent.json) | `14+ 14-` |
|  [chapter.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/chapter.json) | `12+ 12-` |
|  [archivesStory.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/archivesStory.json) | `17+ 6-` |
|  [product_money.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/product_money.json) | `20+` |
|  [partnerEffectUpgrade.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/partnerEffectUpgrade.json) | `18+ 2-` |
|  [npc.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/npc.json) | `20+` |
|  [scene_npc.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/scene_npc.json) | `17+` |
|  [rebate.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/rebate.json) | `5+ 11-` |
|  [chapterreward.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/chapterreward.json) | `16+` |
|  [pvp_race.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pvp_race.json) | `0+ 15-` |
|  [jumptarget.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/jumptarget.json) | `14+` |
|  [achievements.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/achievements.json) | `14+` |
|  [Fragment.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Fragment.json) | `14+` |
|  [hide_moves.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/hide_moves.json) | `12+` |
|  [sp_hide_moves.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/sp_hide_moves.json) | `10+` |
|  [itemsOptimizeCatItems24.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems24.json) | `10+` |
|  [starmap.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/starmap.json) | `4+ 4-` |
|  [achievementbonus.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/achievementbonus.json) | `8+` |
|  [pvp_vote.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pvp_vote.json) | `2+ 2-` |
|  [exchange_clt.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/exchange_clt.json) | `2+ 2-` |
|  [autocardRole.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardRole.json) | `2+ 2-` |

### Removed
| Path | Diff (+/-) |
| :--- | :--- |
|  - | `0` |

