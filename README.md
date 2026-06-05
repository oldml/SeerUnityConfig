[Compare](https://github.com/oldml/SeerUnityConfig/compare/d28da720f2076d1c3a3cc56ded59672db3a279e2...main)

![ConfigPackage](https://img.shields.io/badge/ConfigPackage-20260605021035-blue?style=flat-square)
![DefaultPackage](https://img.shields.io/badge/DefaultPackage-20260605040453-brightgreen?style=flat-square)

> Generated at `2026-06-05 11:40:42 UTC+8` | Branch `main` | Base Commit `d28da72`

```diff
! 67 files changed
+ 33,002 insertions(+)
- 805 deletions(-)
```

### Created
| Path | Diff (+/-) |
| :--- | :--- |
|  [WishMintmark.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/WishMintmark.json) | `3,444+` |
|  [starrySkyStoryConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/starrySkyStoryConfig.json) | `116+` |

### Updated
| Path | Diff (+/-) |
| :--- | :--- |
|  [story_1017.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/story_1017.json) | `15,306+ 5-` |
|  [mintmark.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/mintmark.json) | `3,709+ 1-` |
|  [storyAnniversary2026ChatTalk.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/storyAnniversary2026ChatTalk.json) | `1,342+` |
|  [talk.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/talk.json) | `1,135+ 5-` |
|  [monsters.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/monsters.json) | `873+` |
|  [moves.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/moves.json) | `775+` |
|  [Activity_ShopConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Activity_ShopConfig.json) | `322+ 322-` |
|  [redbadge.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/redbadge.json) | `441+ 58-` |
|  [ActivityCenter.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/ActivityCenter.json) | `382+ 25-` |
|  [product_diamond.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/product_diamond.json) | `381+ 11-` |
|  [Activity_TaskConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Activity_TaskConfig.json) | `384+` |
|  [aurumEndgameExpConfig_adven.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/aurumEndgameExpConfig_adven.json) | `285+ 35-` |
|  [aurumEndgameExpConfig_endless.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/aurumEndgameExpConfig_endless.json) | `149+ 149-` |
|  [skill_effect.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/skill_effect.json) | `270+` |
|  [Wishskin.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Wishskin.json) | `270+` |
|  [midleItems.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/midleItems.json) | `257+ 11-` |
|  [new_super_design.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/new_super_design.json) | `242+` |
|  [jumptarget.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/jumptarget.json) | `231+` |
|  [itemsOptimizeCatItems17.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems17.json) | `195+ 11-` |
|  [effectInfo.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectInfo.json) | `183+ 3-` |
|  [storyAnniversary2026BBS.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/storyAnniversary2026BBS.json) | `180+` |
|  [new_monster_level.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/new_monster_level.json) | `139+ 5-` |
|  [storyAnniversary2026Main.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/storyAnniversary2026Main.json) | `136+ 1-` |
|  [module.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/module.json) | `126+` |
|  [Wishpet.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Wishpet.json) | `126+` |
|  [storyAnniversary2026FreeShop.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/storyAnniversary2026FreeShop.json) | `120+` |
|  [petbook.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/petbook.json) | `108+ 12-` |
|  [chapterpoint.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/chapterpoint.json) | `115+` |
|  [pet_skin.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pet_skin.json) | `108+` |
|  [effectIcon.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectIcon.json) | `103+` |
|  [map.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/map.json) | `94+ 3-` |
|  [buff.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/buff.json) | `88+` |
|  [achievements.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/achievements.json) | `84+` |
|  [profilephoto.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/profilephoto.json) | `30+ 30-` |
|  [aurumEndgameStageConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/aurumEndgameStageConfig.json) | `29+ 30-` |
|  [itemsTip.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsTip.json) | `56+` |
|  [help_tips.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/help_tips.json) | `52+ 4-` |
|  [storymodel.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/storymodel.json) | `55+` |
|  [archivesStory.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/archivesStory.json) | `47+ 3-` |
|  [autoOpenPanel.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autoOpenPanel.json) | `48+` |
|  [aurumEndgameEnemyConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/aurumEndgameEnemyConfig.json) | `23+ 23-` |
|  [Wishsuit.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Wishsuit.json) | `44+` |
|  [product_money.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/product_money.json) | `40+` |
|  [effectDes.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectDes.json) | `40+` |
|  [achievementbonus.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/achievementbonus.json) | `40+` |
|  [pvp_vote.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pvp_vote.json) | `19+ 19-` |
|  [signIcon_fight.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/signIcon_fight.json) | `32+` |
|  [civilizationGameHreoSkill.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/civilizationGameHreoSkill.json) | `14+ 14-` |
|  [guidePetRecommend.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/guidePetRecommend.json) | `27+` |
|  [hide_moves.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/hide_moves.json) | `24+` |
|  [aurumEndgameTutorialConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/aurumEndgameTutorialConfig.json) | `9+ 15-` |
|  [treasure_chest_gift.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/treasure_chest_gift.json) | `23+` |
|  [npc.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/npc.json) | `20+` |
|  [starmap.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/starmap.json) | `16+ 2-` |
|  [active_sort.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/active_sort.json) | `18+` |
|  [PetFightSkinSkillReplace.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/PetFightSkinSkillReplace.json) | `18+` |
|  [Fragment.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Fragment.json) | `14+` |
|  [itemsOptimizeCatItems26.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems26.json) | `11+` |
|  [itemsOptimizeCatItems24.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems24.json) | `10+` |
|  [pet_skin_rewardtype.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pet_skin_rewardtype.json) | `8+` |
|  [Wishpart.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Wishpart.json) | `7+` |
|  [storyAnniversary2026News.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/storyAnniversary2026News.json) | `3+ 3-` |
|  [chapter.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/chapter.json) | `3+ 3-` |
|  [starmaplist.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/starmaplist.json) | `2+ 1-` |
|  [storyAnniversary2026Items.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/storyAnniversary2026Items.json) | `1+ 1-` |

### Removed
| Path | Diff (+/-) |
| :--- | :--- |
|  - | `0` |

