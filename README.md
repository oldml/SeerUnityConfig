[Compare](https://github.com/oldml/SeerUnityConfig/compare/7a68374091a161ae919984d0657576e8fa50403e...main)

![ConfigPackage](https://img.shields.io/badge/ConfigPackage-20260625214558-blue?style=flat-square)
![DefaultPackage](https://img.shields.io/badge/DefaultPackage-20260625223832-brightgreen?style=flat-square)

> Generated at `2026-06-26 11:20:52 UTC+8` | Branch `main` | Base Commit `7a68374`

```diff
! 63 files changed
+ 10,545 insertions(+)
- 649 deletions(-)
```

### Created
| Path | Diff (+/-) |
| :--- | :--- |
|  [story_1025.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/story_1025.json) | `4,954+` |
|  [seerShipChooseGame.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/seerShipChooseGame.json) | `1,024+` |
|  [dayDreamGiftConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/dayDreamGiftConfig.json) | `334+` |
|  [seerShipChooseGameAchievement.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/seerShipChooseGameAchievement.json) | `124+` |
|  [dayDreamStoryConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/dayDreamStoryConfig.json) | `95+` |

### Updated
| Path | Diff (+/-) |
| :--- | :--- |
|  [talk.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/talk.json) | `1,002+ 73-` |
|  [bossInfo.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/bossInfo.json) | `559+ 279-` |
|  [new_super_design.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/new_super_design.json) | `233+` |
|  [monsters.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/monsters.json) | `214+ 1-` |
|  [moves.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/moves.json) | `194+` |
|  [ActivityCenter.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/ActivityCenter.json) | `146+ 27-` |
|  [redbadge.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/redbadge.json) | `141+ 7-` |
|  [guidePetRecommend.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/guidePetRecommend.json) | `135+` |
|  [effectIcon.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectIcon.json) | `114+ 7-` |
|  [autocardContent.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardContent.json) | `51+ 51-` |
|  [chapterpoint.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/chapterpoint.json) | `94+ 2-` |
|  [product_diamond.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/product_diamond.json) | `90+` |
|  [partner.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/partner.json) | `49+ 35-` |
|  [new_monster_level.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/new_monster_level.json) | `73+ 9-` |
|  [autocardSeasonEffect.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardSeasonEffect.json) | `33+ 33-` |
|  [skill_effect.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/skill_effect.json) | `60+` |
|  [midleItems.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/midleItems.json) | `60+` |
|  [module.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/module.json) | `56+` |
|  [storyAnniversary2026FreeShop.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/storyAnniversary2026FreeShop.json) | `24+ 24-` |
|  [itemsOptimizeCatItems17.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems17.json) | `46+` |
|  [exchange_clt.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/exchange_clt.json) | `44+` |
|  [Fragment.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Fragment.json) | `42+` |
|  [pet_skin.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pet_skin.json) | `36+` |
|  [mintmark.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/mintmark.json) | `36+` |
|  [LimitedAdastraActivityReward.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/LimitedAdastraActivityReward.json) | `18+ 18-` |
|  [chapter.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/chapter.json) | `30+ 3-` |
|  [signIcon_fight.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/signIcon_fight.json) | `32+` |
|  [effectDes.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectDes.json) | `31+ 1-` |
|  [npc.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/npc.json) | `30+` |
|  [itemsOptimizeCatItems24.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems24.json) | `30+` |
|  [achievements.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/achievements.json) | `22+ 8-` |
|  [storymodel.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/storymodel.json) | `25+ 3-` |
|  [petbook.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/petbook.json) | `17+ 11-` |
|  [autocardRole.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardRole.json) | `14+ 14-` |
|  [map_config.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/map_config.json) | `26+` |
|  [partnerEffectUpgrade.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/partnerEffectUpgrade.json) | `21+` |
|  [jumptarget.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/jumptarget.json) | `21+` |
|  [archivesStory.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/archivesStory.json) | `16+ 5-` |
|  [buff.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/buff.json) | `20+` |
|  [rebate.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/rebate.json) | `11+ 5-` |
|  [itemsTip.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsTip.json) | `16+` |
|  [autocardPlayer.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardPlayer.json) | `8+ 8-` |
|  [starmaplist.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/starmaplist.json) | `6+ 6-` |
|  [hide_moves.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/hide_moves.json) | `12+` |
|  [autoOpenPanel.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autoOpenPanel.json) | `12+` |
|  [AdAstraGalaxy.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/AdAstraGalaxy.json) | `6+ 6-` |
|  [sp_hide_moves.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/sp_hide_moves.json) | `10+` |
|  [product_money.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/product_money.json) | `10+` |
|  [chapterreward.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/chapterreward.json) | `9+ 1-` |
|  [effectInfo.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectInfo.json) | `9+` |
|  [achievementbonus.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/achievementbonus.json) | `8+` |
|  [pvp_race.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pvp_race.json) | `0+ 6-` |
|  [starmap.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/starmap.json) | `3+ 1-` |
|  [map.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/map.json) | `2+ 2-` |
|  [autoCardBuffWiki.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autoCardBuffWiki.json) | `4+` |
|  [story_1016.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/story_1016.json) | `1+ 1-` |
|  [help_tips.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/help_tips.json) | `1+ 1-` |
|  [autocardSession.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardSession.json) | `1+ 1-` |

### Removed
| Path | Diff (+/-) |
| :--- | :--- |
|  - | `0` |

