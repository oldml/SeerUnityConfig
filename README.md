[Compare](https://github.com/oldml/SeerUnityConfig/compare/fc9060fa39ae0b04b0a9c2ef2d908b998a1cd4ee...main)

![ConfigPackage](https://img.shields.io/badge/ConfigPackage-20260416232201-blue?style=flat-square)
![DefaultPackage](https://img.shields.io/badge/DefaultPackage-20260417010718-brightgreen?style=flat-square)

> Generated at `2026-04-17 12:20:41 UTC+8` | Branch `main` | Base Commit `fc9060f`

```diff
! 63 files changed
+ 18,770 insertions(+)
- 1,780 deletions(-)
```

### Created
| Path | Diff (+/-) |
| :--- | :--- |
|  [borucashop.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/borucashop.json) | `58+` |
|  [boruca_strategy.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/boruca_strategy.json) | `49+` |

### Updated
| Path | Diff (+/-) |
| :--- | :--- |
|  [story_1016.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/story_1016.json) | `12,828+ 2-` |
|  [moves.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/moves.json) | `979+ 19-` |
|  [autocardContent.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardContent.json) | `43+ 718-` |
|  [pet_skin.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pet_skin.json) | `405+ 351-` |
|  [monsters.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/monsters.json) | `553+ 5-` |
|  [signIcon_fight.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/signIcon_fight.json) | `290+ 164-` |
|  [new_monster_level.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/new_monster_level.json) | `285+ 9-` |
|  [product_diamond.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/product_diamond.json) | `242+ 2-` |
|  [new_super_design.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/new_super_design.json) | `242+` |
|  [effectInfo.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectInfo.json) | `190+ 48-` |
|  [pet_skin_reward.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pet_skin_reward.json) | `183+ 48-` |
|  [skill_effect.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/skill_effect.json) | `217+ 7-` |
|  [talk.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/talk.json) | `174+ 39-` |
|  [itemsOptimizeCatItems17.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems17.json) | `184+` |
|  [battlepass_shop.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/battlepass_shop.json) | `115+ 43-` |
|  [midleItems.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/midleItems.json) | `146+ 2-` |
|  [buff.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/buff.json) | `139+ 1-` |
|  [ActivityCenter.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/ActivityCenter.json) | `116+ 14-` |
|  [chapterpoint.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/chapterpoint.json) | `119+ 4-` |
|  [JackPotShop.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/JackPotShop.json) | `8+ 113-` |
|  [guidePetRecommend.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/guidePetRecommend.json) | `110+ 2-` |
|  [redbadge.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/redbadge.json) | `105+ 5-` |
|  [achievements.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/achievements.json) | `56+ 42-` |
|  [petbook.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/petbook.json) | `62+ 11-` |
|  [effectDes.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectDes.json) | `71+ 1-` |
|  [profilephoto.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/profilephoto.json) | `69+ 1-` |
|  [module.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/module.json) | `70+` |
|  [pvp_ban.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pvp_ban.json) | `28+ 27-` |
|  [effectIcon.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectIcon.json) | `53+ 1-` |
|  [sp_hide_moves.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/sp_hide_moves.json) | `50+` |
|  [itemsTip.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsTip.json) | `48+` |
|  [map.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/map.json) | `44+` |
|  [Activity_TaskConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Activity_TaskConfig.json) | `22+ 22-` |
|  [jumptarget.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/jumptarget.json) | `42+` |
|  [achievementbonus.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/achievementbonus.json) | `40+` |
|  [treasure_chest_gift.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/treasure_chest_gift.json) | `37+` |
|  [pvp_task.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pvp_task.json) | `18+ 18-` |
|  [autocardRole.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardRole.json) | `17+ 17-` |
|  [Fragment.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Fragment.json) | `28+` |
|  [map_config.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/map_config.json) | `26+` |
|  [pvp_achieve.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pvp_achieve.json) | `12+ 12-` |
|  [hide_moves.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/hide_moves.json) | `24+` |
|  [itemsOptimizeCatItems24.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems24.json) | `21+ 1-` |
|  [active_sort.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/active_sort.json) | `21+ 1-` |
|  [archivesStory.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/archivesStory.json) | `15+ 4-` |
|  [autocardBuff.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardBuff.json) | `18+` |
|  [autoOpenPanel.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autoOpenPanel.json) | `14+ 2-` |
|  [pvp_expert_seasonrank.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pvp_expert_seasonrank.json) | `13+` |
|  [chapterreward.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/chapterreward.json) | `10+ 2-` |
|  [itemsOptimizeCatItems26.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems26.json) | `11+` |
|  [classicSweepInfo.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/classicSweepInfo.json) | `11+` |
|  [pvp_ban_expert.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pvp_ban_expert.json) | `5+ 5-` |
|  [pvp_vote.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pvp_vote.json) | `4+ 4-` |
|  [pvp_shop.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pvp_shop.json) | `4+ 4-` |
|  [pet_skin_rewardtype.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pet_skin_rewardtype.json) | `8+` |
|  [help_tips.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/help_tips.json) | `8+` |
|  [pvp_reward.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pvp_reward.json) | `3+ 3-` |
|  [itemsOptimizeCatItems3.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems3.json) | `3+ 3-` |
|  [starmap.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/starmap.json) | `2+ 1-` |
|  [storymodel.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/storymodel.json) | `1+ 1-` |
|  [battlepass_reward.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/battlepass_reward.json) | `1+ 1-` |

### Removed
| Path | Diff (+/-) |
| :--- | :--- |
|  - | `0` |

