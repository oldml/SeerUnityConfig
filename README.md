[Compare](https://github.com/oldml/SeerUnityConfig/compare/9ee345fe5b39c19513c58623c8bacff76cd68a71...main)

![ConfigPackage](https://img.shields.io/badge/ConfigPackage-20260528225042-blue?style=flat-square)
![DefaultPackage](https://img.shields.io/badge/DefaultPackage-20260528231200-brightgreen?style=flat-square)

> Generated at `2026-05-29 11:00:52 UTC+8` | Branch `main` | Base Commit `9ee345f`

```diff
! 65 files changed
+ 21,208 insertions(+)
- 865 deletions(-)
```

### Created
| Path | Diff (+/-) |
| :--- | :--- |
|  - | `0` |

### Updated
| Path | Diff (+/-) |
| :--- | :--- |
|  [story_1017.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/story_1017.json) | `10,817+ 26-` |
|  [storyAnniversary2026ChatTalk.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/storyAnniversary2026ChatTalk.json) | `2,442+` |
|  [bossInfo.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/bossInfo.json) | `805+ 245-` |
|  [storyAnniversary2026SideQuests.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/storyAnniversary2026SideQuests.json) | `770+` |
|  [moves.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/moves.json) | `620+` |
|  [monsters.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/monsters.json) | `518+ 2-` |
|  [aurumEndgameExpConfig_endless.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/aurumEndgameExpConfig_endless.json) | `500+` |
|  [Activity_ShopConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Activity_ShopConfig.json) | `231+ 231-` |
|  [storyAnniversary2026BBS.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/storyAnniversary2026BBS.json) | `392+ 5-` |
|  [itemsOptimizeCatItems17.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems17.json) | `392+ 1-` |
|  [storyAnniversary2026Main.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/storyAnniversary2026Main.json) | `351+` |
|  [redbadge.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/redbadge.json) | `267+ 8-` |
|  [profilephoto.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/profilephoto.json) | `255+` |
|  [new_super_design.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/new_super_design.json) | `242+` |
|  [product_diamond.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/product_diamond.json) | `220+` |
|  [storyAnniversary2026FreeShop.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/storyAnniversary2026FreeShop.json) | `192+ 12-` |
|  [ActivityCenter.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/ActivityCenter.json) | `163+ 27-` |
|  [new_monster_level.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/new_monster_level.json) | `176+ 4-` |
|  [aurumEndgameOptionsConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/aurumEndgameOptionsConfig.json) | `86+ 86-` |
|  [skill_effect.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/skill_effect.json) | `150+` |
|  [midleItems.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/midleItems.json) | `150+` |
|  [chapterpoint.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/chapterpoint.json) | `138+` |
|  [aurumEndgameStageConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/aurumEndgameStageConfig.json) | `63+ 61-` |
|  [guidePetRecommend.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/guidePetRecommend.json) | `112+ 4-` |
|  [effectInfo.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectInfo.json) | `102+ 1-` |
|  [autocardBuff.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardBuff.json) | `99+` |
|  [Activity_TaskConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Activity_TaskConfig.json) | `96+` |
|  [effectIcon.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectIcon.json) | `81+ 4-` |
|  [buff.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/buff.json) | `80+` |
|  [signIcon_fight.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/signIcon_fight.json) | `51+ 24-` |
|  [petbook.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/petbook.json) | `44+ 15-` |
|  [effectDes.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectDes.json) | `46+ 6-` |
|  [aurumEndgameEnemyConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/aurumEndgameEnemyConfig.json) | `23+ 23-` |
|  [module.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/module.json) | `42+` |
|  [awakendetail.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/awakendetail.json) | `41+` |
|  [sp_hide_moves.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/sp_hide_moves.json) | `40+` |
|  [pet_skin.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pet_skin.json) | `36+` |
|  [LimitedAdastraActivityReward.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/LimitedAdastraActivityReward.json) | `18+ 18-` |
|  [jumptarget.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/jumptarget.json) | `35+` |
|  [aurumEndgameExpConfig_adven.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/aurumEndgameExpConfig_adven.json) | `17+ 17-` |
|  [product_money.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/product_money.json) | `30+` |
|  [itemsTip.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsTip.json) | `29+ 1-` |
|  [Fragment.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Fragment.json) | `28+` |
|  [archivesStory.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/archivesStory.json) | `24+ 2-` |
|  [hide_moves.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/hide_moves.json) | `24+` |
|  [exchange_clt.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/exchange_clt.json) | `22+` |
|  [itemsOptimizeCatItems24.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems24.json) | `20+` |
|  [awakenlist.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/awakenlist.json) | `9+ 9-` |
|  [rebate.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/rebate.json) | `11+ 5-` |
|  [help_tips.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/help_tips.json) | `16+` |
|  [achievementbonus.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/achievementbonus.json) | `16+` |
|  [achievements.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/achievements.json) | `14+` |
|  [storyAnniversary2026Items.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/storyAnniversary2026Items.json) | `6+ 6-` |
|  [AdAstraGalaxy.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/AdAstraGalaxy.json) | `6+ 6-` |
|  [classicSweepInfo.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/classicSweepInfo.json) | `11+` |
|  [storyAnniversary2026News.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/storyAnniversary2026News.json) | `4+ 4-` |
|  [open_bonus.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/open_bonus.json) | `8+` |
|  [monthpet.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/monthpet.json) | `4+ 4-` |
|  [vip_month_monster.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/vip_month_monster.json) | `3+ 3-` |
|  [awakenbosslevel.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/awakenbosslevel.json) | `6+` |
|  [open_time_limit.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/open_time_limit.json) | `5+` |
|  [shop_gift.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/shop_gift.json) | `2+ 2-` |
|  [dailytask.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/dailytask.json) | `2+ 2-` |
|  [awakenbossconfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/awakenbossconfig.json) | `4+` |
|  [battle_effects.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/battle_effects.json) | `1+ 1-` |

### Removed
| Path | Diff (+/-) |
| :--- | :--- |
|  - | `0` |

