[Compare](https://github.com/oldml/SeerUnityConfig/compare/857c047c37d586edfea056d1d5555280dd89ece0...main)

![ConfigPackage](https://img.shields.io/badge/ConfigPackage-20260717002754-blue?style=flat-square)
![DefaultPackage](https://img.shields.io/badge/DefaultPackage-20260717001055-brightgreen?style=flat-square)

> Generated at `2026-07-17 11:01:20 UTC+8` | Branch `main` | Base Commit `857c047`

```diff
! 66 files changed
+ 12,096 insertions(+)
- 486 deletions(-)
```

### Created
| Path | Diff (+/-) |
| :--- | :--- |
|  [Activity_TimeUpdateConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Activity_TimeUpdateConfig.json) | `26+` |

### Updated
| Path | Diff (+/-) |
| :--- | :--- |
|  [story_1025.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/story_1025.json) | `7,646+ 1-` |
|  [moves.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/moves.json) | `715+` |
|  [monsters.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/monsters.json) | `468+ 8-` |
|  [skill_effect.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/skill_effect.json) | `286+ 1-` |
|  [AbyssFisheryLevel.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/AbyssFisheryLevel.json) | `140+ 140-` |
|  [new_super_design.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/new_super_design.json) | `233+` |
|  [effectInfo.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectInfo.json) | `175+` |
|  [battlepass_shop.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/battlepass_shop.json) | `122+ 50-` |
|  [itemsOptimizeCatItems17.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems17.json) | `139+ 1-` |
|  [signIcon_fight.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/signIcon_fight.json) | `137+ 2-` |
|  [guidePetRecommend.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/guidePetRecommend.json) | `135+` |
|  [product_diamond.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/product_diamond.json) | `110+` |
|  [autocardContent.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardContent.json) | `51+ 51-` |
|  [chapterpoint.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/chapterpoint.json) | `92+` |
|  [effectDes.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectDes.json) | `90+` |
|  [new_monster_level.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/new_monster_level.json) | `72+ 16-` |
|  [ActivityCenter.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/ActivityCenter.json) | `78+ 10-` |
|  [profilephoto.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/profilephoto.json) | `85+` |
|  [AbyssFishery.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/AbyssFishery.json) | `80+` |
|  [redbadge.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/redbadge.json) | `72+ 5-` |
|  [AbyssFisheryShop.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/AbyssFisheryShop.json) | `77+` |
|  [pet_skin.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pet_skin.json) | `72+` |
|  [midleItems.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/midleItems.json) | `66+` |
|  [achievements.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/achievements.json) | `58+ 2-` |
|  [petbook.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/petbook.json) | `39+ 16-` |
|  [pvp_ban.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pvp_ban.json) | `26+ 28-` |
|  [map.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/map.json) | `50+ 4-` |
|  [effectIcon.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectIcon.json) | `52+` |
|  [sp_hide_moves.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/sp_hide_moves.json) | `50+` |
|  [treasure_chest_gift.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/treasure_chest_gift.json) | `49+` |
|  [itemsOptimizeCatItems13.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems13.json) | `48+` |
|  [pvp_expert_seasonrank.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pvp_expert_seasonrank.json) | `30+ 17-` |
|  [Activity_TaskConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Activity_TaskConfig.json) | `22+ 22-` |
|  [module.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/module.json) | `42+` |
|  [Fragment.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Fragment.json) | `42+` |
|  [buff.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/buff.json) | `38+` |
|  [vip_pet_shop.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/vip_pet_shop.json) | `18+ 18-` |
|  [pvp_task.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pvp_task.json) | `18+ 18-` |
|  [itemsTip.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsTip.json) | `36+` |
|  [awakenlist.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/awakenlist.json) | `36+` |
|  [storymodel.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/storymodel.json) | `28+ 6-` |
|  [achievementbonus.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/achievementbonus.json) | `32+` |
|  [itemsOptimizeCatItems24.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems24.json) | `30+` |
|  [pvp_achieve.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pvp_achieve.json) | `12+ 12-` |
|  [help_tips.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/help_tips.json) | `24+` |
|  [autocardBuff.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardBuff.json) | `21+ 3-` |
|  [product_money.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/product_money.json) | `0+ 20-` |
|  [map_config.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/map_config.json) | `18+` |
|  [chapterreward.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/chapterreward.json) | `16+` |
|  [jumptarget.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/jumptarget.json) | `11+ 4-` |
|  [archivesStory.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/archivesStory.json) | `13+ 2-` |
|  [suit.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/suit.json) | `12+` |
|  [hide_moves.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/hide_moves.json) | `12+` |
|  [itemsOptimizeCatItems26.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems26.json) | `11+` |
|  [starmap.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/starmap.json) | `6+ 4-` |
|  [pvp_ban_expert.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pvp_ban_expert.json) | `5+ 5-` |
|  [pvp_shop.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pvp_shop.json) | `4+ 4-` |
|  [pvp_vote.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pvp_vote.json) | `3+ 3-` |
|  [pvp_reward.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pvp_reward.json) | `3+ 3-` |
|  [autocardRole.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardRole.json) | `3+ 3-` |
|  [open_time_limit.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/open_time_limit.json) | `5+` |
|  [autoOpenPanel.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autoOpenPanel.json) | `2+ 2-` |
|  [activityTimeControl.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/activityTimeControl.json) | `2+ 2-` |
|  [starmaplist.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/starmaplist.json) | `1+ 2-` |
|  [battlepass_reward.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/battlepass_reward.json) | `1+ 1-` |

### Removed
| Path | Diff (+/-) |
| :--- | :--- |
|  - | `0` |

