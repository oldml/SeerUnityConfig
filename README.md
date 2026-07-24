[Compare](https://github.com/oldml/SeerUnityConfig/compare/248477b218d355740aecd9c02c647d0b8eb0a589...main)

![ConfigPackage](https://img.shields.io/badge/ConfigPackage-20260723220442-blue?style=flat-square)
![DefaultPackage](https://img.shields.io/badge/DefaultPackage-20260723211820-brightgreen?style=flat-square)

> Generated at `2026-07-24 11:01:07 UTC+8` | Branch `main` | Base Commit `248477b`

```diff
! 49 files changed
+ 9,051 insertions(+)
- 524 deletions(-)
```

### Created
| Path | Diff (+/-) |
| :--- | :--- |
|  [story_1026.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/story_1026.json) | `5,504+` |
|  [pvpCostMode_vote.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pvpCostMode_vote.json) | `88+` |
|  [pvpCostMode_cost.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pvpCostMode_cost.json) | `39+` |
|  [pvpCostMode_votePrice.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pvpCostMode_votePrice.json) | `24+` |

### Updated
| Path | Diff (+/-) |
| :--- | :--- |
|  [bossInfo.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/bossInfo.json) | `599+ 319-` |
|  [moves.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/moves.json) | `482+ 26-` |
|  [monsters.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/monsters.json) | `385+ 2-` |
|  [new_super_design.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/new_super_design.json) | `242+` |
|  [skill_effect.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/skill_effect.json) | `131+ 11-` |
|  [product_diamond.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/product_diamond.json) | `120+` |
|  [redbadge.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/redbadge.json) | `107+ 8-` |
|  [effectInfo.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectInfo.json) | `99+ 11-` |
|  [guidePetRecommend.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/guidePetRecommend.json) | `108+` |
|  [ActivityCenter.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/ActivityCenter.json) | `85+ 17-` |
|  [chapterpoint.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/chapterpoint.json) | `92+` |
|  [new_monster_level.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/new_monster_level.json) | `85+ 3-` |
|  [buff.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/buff.json) | `78+` |
|  [midleItems.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/midleItems.json) | `72+` |
|  [itemsOptimizeCatItems17.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems17.json) | `69+` |
|  [effectIcon.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectIcon.json) | `55+ 3-` |
|  [petbook.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/petbook.json) | `23+ 33-` |
|  [module.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/module.json) | `49+` |
|  [exchange_clt.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/exchange_clt.json) | `44+` |
|  [Fragment.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Fragment.json) | `42+` |
|  [awakendetail.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/awakendetail.json) | `41+` |
|  [pet_skin.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pet_skin.json) | `36+` |
|  [awakenlist.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/awakenlist.json) | `18+ 18-` |
|  [autocardContent.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardContent.json) | `18+ 18-` |
|  [Unbindmintinfo.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Unbindmintinfo.json) | `36+` |
|  [LimitedAdastraActivityReward.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/LimitedAdastraActivityReward.json) | `18+ 18-` |
|  [signIcon_fight.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/signIcon_fight.json) | `33+ 1-` |
|  [itemsOptimizeCatItems24.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems24.json) | `30+` |
|  [effectDes.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectDes.json) | `30+` |
|  [chapter.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/chapter.json) | `27+` |
|  [jumptarget.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/jumptarget.json) | `13+ 6-` |
|  [itemsTip.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsTip.json) | `17+ 1-` |
|  [hide_moves.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/hide_moves.json) | `18+` |
|  [rebate.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/rebate.json) | `11+ 5-` |
|  [autocardRole.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardRole.json) | `8+ 8-` |
|  [archivesStory.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/archivesStory.json) | `13+ 2-` |
|  [story_1025.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/story_1025.json) | `7+ 7-` |
|  [achievements.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/achievements.json) | `14+` |
|  [AdAstraGalaxy.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/AdAstraGalaxy.json) | `6+ 6-` |
|  [help_tips.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/help_tips.json) | `8+` |
|  [chapterreward.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/chapterreward.json) | `8+` |
|  [achievementbonus.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/achievementbonus.json) | `8+` |
|  [awakenbosslevel.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/awakenbosslevel.json) | `6+` |
|  [awakenbossconfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/awakenbossconfig.json) | `4+` |
|  [pvp_ban_expert.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pvp_ban_expert.json) | `1+ 1-` |

### Removed
| Path | Diff (+/-) |
| :--- | :--- |
|  - | `0` |

