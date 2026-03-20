[Compare](https://github.com/oldml/SeerUnityConfig/compare/973f78a59ccb1c002b46030d773dba2769cc8084...main)

![ConfigPackage](https://img.shields.io/badge/ConfigPackage-20260320111720-blue?style=flat-square)
![DefaultPackage](https://img.shields.io/badge/DefaultPackage-20260319211912-brightgreen?style=flat-square)

> Generated at `2026-03-20 12:01:20 UTC+8` | Branch `main` | Base Commit `973f78a`

```diff
! 54 files changed
+ 12,417 insertions(+)
- 240 deletions(-)
```

### Created
| Path | Diff (+/-) |
| :--- | :--- |
|  [stg_skill.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/stg_skill.json) | `67+` |
|  [spiderSolitaireGame.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/spiderSolitaireGame.json) | `44+` |
|  [AdAstraShop.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/AdAstraShop.json) | `22+` |

### Updated
| Path | Diff (+/-) |
| :--- | :--- |
|  [story_1015.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/story_1015.json) | `7,647+ 2-` |
|  [Activity_TaskConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Activity_TaskConfig.json) | `1,024+` |
|  [mintmark.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/mintmark.json) | `436+` |
|  [moves.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/moves.json) | `321+ 12-` |
|  [redbadge.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/redbadge.json) | `316+ 2-` |
|  [new_super_design.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/new_super_design.json) | `242+` |
|  [talk.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/talk.json) | `237+ 3-` |
|  [monsters.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/monsters.json) | `234+ 2-` |
|  [ActivityCenter.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/ActivityCenter.json) | `172+ 2-` |
|  [product_diamond.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/product_diamond.json) | `160+` |
|  [skill_effect.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/skill_effect.json) | `120+` |
|  [effectDes.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectDes.json) | `90+ 20-` |
|  [new_monster_level.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/new_monster_level.json) | `83+ 21-` |
|  [profilephoto.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/profilephoto.json) | `102+` |
|  [chapterpoint.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/chapterpoint.json) | `96+ 4-` |
|  [midleItems.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/midleItems.json) | `96+` |
|  [effectInfo.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectInfo.json) | `77+ 1-` |
|  [effectIcon.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectIcon.json) | `62+ 10-` |
|  [jumptarget.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/jumptarget.json) | `53+ 18-` |
|  [itemsOptimizeCatItems17.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems17.json) | `69+` |
|  [module.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/module.json) | `63+` |
|  [buff.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/buff.json) | `58+` |
|  [pvp_ban.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pvp_ban.json) | `28+ 27-` |
|  [guidePetRecommend.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/guidePetRecommend.json) | `54+` |
|  [petbook.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/petbook.json) | `17+ 33-` |
|  [Unbindmintinfo.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Unbindmintinfo.json) | `48+` |
|  [signIcon_fight.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/signIcon_fight.json) | `42+ 1-` |
|  [pet_skin.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pet_skin.json) | `39+ 3-` |
|  [awakendetail.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/awakendetail.json) | `41+` |
|  [sp_hide_moves.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/sp_hide_moves.json) | `40+` |
|  [help_tips.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/help_tips.json) | `40+` |
|  [awakenlist.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/awakenlist.json) | `18+ 18-` |
|  [storymodel.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/storymodel.json) | `22+` |
|  [itemsTip.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsTip.json) | `16+` |
|  [battle_effects.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/battle_effects.json) | `15+` |
|  [archivesStory.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/archivesStory.json) | `13+ 2-` |
|  [achievements.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/achievements.json) | `14+` |
|  [Fragment.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Fragment.json) | `14+` |
|  [hide_moves.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/hide_moves.json) | `12+` |
|  [classicSweepInfo.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/classicSweepInfo.json) | `11+` |
|  [itemsOptimizeCatItems24.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems24.json) | `10+` |
|  [achievementbonus.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/achievementbonus.json) | `8+` |
|  [dungeon_enter.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/dungeon_enter.json) | `5+ 1-` |
|  [awakenbosslevel.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/awakenbosslevel.json) | `6+` |
|  [starmap.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/starmap.json) | `2+ 2-` |
|  [pvp_vote.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pvp_vote.json) | `2+ 2-` |
|  [pvp_ban_expert.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pvp_ban_expert.json) | `2+ 2-` |
|  [map.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/map.json) | `2+ 2-` |
|  [awakenbossconfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/awakenbossconfig.json) | `4+` |
|  [chapterreward.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/chapterreward.json) | `1+ 1-` |

### Removed
| Path | Diff (+/-) |
| :--- | :--- |
|  ~[pvp_practice.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pvp_practice.json)~ | `0+ 49-` |

