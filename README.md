[Compare](https://github.com/oldml/SeerUnityConfig/compare/9bb0cec3cc0239e31fc77839bb5d364817273b62...main)

![ConfigPackage](https://img.shields.io/badge/ConfigPackage-20260327002822-blue?style=flat-square)
![DefaultPackage](https://img.shields.io/badge/DefaultPackage-20260327001033-brightgreen?style=flat-square)

> Generated at `2026-03-27 11:40:45 UTC+8` | Branch `main` | Base Commit `9bb0cec`

```diff
! 117 files changed
+ 315,853 insertions(+)
- 526 deletions(-)
```

### Created
| Path | Diff (+/-) |
| :--- | :--- |
|  [AdventureStory.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/AdventureStory.json) | `212,543+` |
|  [twelveYearsPromise.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/twelveYearsPromise.json) | `22,844+` |
|  [gainWay.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/gainWay.json) | `19,264+` |
|  [side_effect.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/side_effect.json) | `10,121+` |
|  [AdventureChapter.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/AdventureChapter.json) | `6,625+` |
|  [story_1022.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/story_1022.json) | `5,702+` |
|  [autocardContent.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardContent.json) | `5,452+` |
|  [newguideStep2020.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/newguideStep2020.json) | `3,714+` |
|  [starmap_temp.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/starmap_temp.json) | `3,047+` |
|  [new_starmap.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/new_starmap.json) | `2,586+` |
|  [journey_content.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/journey_content.json) | `1,978+` |
|  [scene_wildboss.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/scene_wildboss.json) | `1,579+` |
|  [Bravechalltask.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Bravechalltask.json) | `1,512+` |
|  [Bravecommtask.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Bravecommtask.json) | `1,460+` |
|  [autocardBuff.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardBuff.json) | `1,399+` |
|  [product_coins.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/product_coins.json) | `918+` |
|  [mapdrop.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/mapdrop.json) | `804+` |
|  [pveEnter.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pveEnter.json) | `708+` |
|  [LockedSpaceMapConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/LockedSpaceMapConfig.json) | `636+` |
|  [tutorial_talk.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/tutorial_talk.json) | `571+` |
|  [pass_task.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pass_task.json) | `546+` |
|  [LimitUseItemInfo.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/LimitUseItemInfo.json) | `532+` |
|  [LockedSpaceRoomConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/LockedSpaceRoomConfig.json) | `498+` |
|  [bottlebonus.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/bottlebonus.json) | `474+` |
|  [fightTestLevelConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/fightTestLevelConfig.json) | `438+` |
|  [awakentask.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/awakentask.json) | `400+` |
|  [announcement.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/announcement.json) | `400+` |
|  [brave_tower.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/brave_tower.json) | `394+` |
|  [autocardRole.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardRole.json) | `384+` |
|  [fightLabBossConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/fightLabBossConfig.json) | `382+` |
|  [ninjaroom.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/ninjaroom.json) | `363+` |
|  [Startrekbossconfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Startrekbossconfig.json) | `316+` |
|  [autocardCV.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardCV.json) | `274+` |
|  [tutorial_recruitlevel.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/tutorial_recruitlevel.json) | `260+` |
|  [BackFlowTask.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/BackFlowTask.json) | `257+` |
|  [latestActivity_temp.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/latestActivity_temp.json) | `254+` |
|  [journey_level.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/journey_level.json) | `246+` |
|  [pvp_MonsterConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pvp_MonsterConfig.json) | `238+` |
|  [redbutton.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/redbutton.json) | `222+` |
|  [new_starmaplist.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/new_starmaplist.json) | `216+` |
|  [awakenlevel.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/awakenlevel.json) | `214+` |
|  [autoCardRecom.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autoCardRecom.json) | `164+` |
|  [pvp_BossConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pvp_BossConfig.json) | `160+` |
|  [autoCardVideo.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autoCardVideo.json) | `144+` |
|  [pvp_practice.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pvp_practice.json) | `141+` |
|  [autocardEffect.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardEffect.json) | `139+` |
|  [diamon_task.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/diamon_task.json) | `125+` |
|  [h5_12th_box.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/h5_12th_box.json) | `112+` |
|  [autocardShop.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardShop.json) | `82+` |
|  [mainLine_chapter.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/mainLine_chapter.json) | `76+` |
|  [h5_12th_task.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/h5_12th_task.json) | `76+` |
|  [diamon_box.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/diamon_box.json) | `76+` |
|  [learningpower_tower.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/learningpower_tower.json) | `64+` |
|  [exp_tower.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/exp_tower.json) | `64+` |
|  [autocardCondition.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardCondition.json) | `64+` |
|  [toolbar.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/toolbar.json) | `52+` |
|  [TeamTaskMonsters.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/TeamTaskMonsters.json) | `51+` |
|  [autocardEffectIconDes.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardEffectIconDes.json) | `46+` |
|  [TitleBg.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/TitleBg.json) | `42+` |
|  [TeamTasks.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/TeamTasks.json) | `41+` |
|  [autocardPlayer.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardPlayer.json) | `40+` |
|  [autoCardbook.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autoCardbook.json) | `39+` |
|  [package_update.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/package_update.json) | `34+` |
|  [autocardNature.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardNature.json) | `34+` |
|  [autoCardBuffWiki.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autoCardBuffWiki.json) | `32+` |
|  [autocardScreen.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardScreen.json) | `24+` |
|  [PreferentialBest.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/PreferentialBest.json) | `24+` |
|  [PremiumPetInfo.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/PremiumPetInfo.json) | `14+` |
|  [shopbanner.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/shopbanner.json) | `13+` |
|  [autocardSkin.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/autocardSkin.json) | `12+` |
|  [FrameInfo.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/FrameInfo.json) | `10+` |
|  [scene_icon.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/scene_icon.json) | `1+` |
|  [profilephotoAutoGive.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/profilephotoAutoGive.json) | `1+` |

### Updated
| Path | Diff (+/-) |
| :--- | :--- |
|  [elvenkingtrial_exchange.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/elvenkingtrial_exchange.json) | `271+ 272-` |
|  [monsters.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/monsters.json) | `322+` |
|  [redbadge.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/redbadge.json) | `302+ 4-` |
|  [new_super_design.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/new_super_design.json) | `233+` |
|  [ActivityCenter.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/ActivityCenter.json) | `198+ 11-` |
|  [itemsOptimizeCatItems17.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems17.json) | `186+ 2-` |
|  [module.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/module.json) | `168+` |
|  [buff.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/buff.json) | `87+ 77-` |
|  [moves.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/moves.json) | `159+` |
|  [product_diamond.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/product_diamond.json) | `141+ 1-` |
|  [pet_skin.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pet_skin.json) | `120+ 12-` |
|  [stg_skill.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/stg_skill.json) | `83+ 40-` |
|  [chapterpoint.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/chapterpoint.json) | `115+` |
|  [midleItems.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/midleItems.json) | `85+ 1-` |
|  [guidePetRecommend.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/guidePetRecommend.json) | `81+` |
|  [elfGachaReward.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/elfGachaReward.json) | `37+ 37-` |
|  [petbook.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/petbook.json) | `59+ 9-` |
|  [new_monster_level.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/new_monster_level.json) | `62+ 4-` |
|  [profilephoto.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/profilephoto.json) | `38+ 21-` |
|  [jumptarget.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/jumptarget.json) | `49+` |
|  [achievements.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/achievements.json) | `29+ 2-` |
|  [AdAstraShop.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/AdAstraShop.json) | `16+ 14-` |
|  [chapter.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/chapter.json) | `28+ 1-` |
|  [itemsTip.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsTip.json) | `28+` |
|  [effectIcon.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/effectIcon.json) | `26+ 1-` |
|  [pet_skin_reward.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pet_skin_reward.json) | `22+` |
|  [active_sort.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/active_sort.json) | `18+` |
|  [rebate.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/rebate.json) | `11+ 5-` |
|  [archivesStory.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/archivesStory.json) | `13+ 2-` |
|  [Fragment.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Fragment.json) | `14+` |
|  [storymodel.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/storymodel.json) | `12+ 1-` |
|  [classicSweepInfo.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/classicSweepInfo.json) | `11+` |
|  [itemsOptimizeCatItems24.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems24.json) | `10+` |
|  [help_tips.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/help_tips.json) | `9+ 1-` |
|  [pet_skin_rewardtype.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pet_skin_rewardtype.json) | `8+` |
|  [chapterreward.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/chapterreward.json) | `8+` |
|  [achievementbonus.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/achievementbonus.json) | `8+` |
|  [hide_moves.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/hide_moves.json) | `6+` |
|  [skill_effect.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/skill_effect.json) | `2+ 2-` |
|  [partnerEffectUpgrade.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/partnerEffectUpgrade.json) | `2+ 2-` |
|  [elfGacha.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/elfGacha.json) | `2+ 2-` |
|  [achievement_rule.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/achievement_rule.json) | `4+` |
|  [story_1015.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/story_1015.json) | `1+ 1-` |
|  [dailytask.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/dailytask.json) | `1+ 1-` |

### Removed
| Path | Diff (+/-) |
| :--- | :--- |
|  - | `0` |

