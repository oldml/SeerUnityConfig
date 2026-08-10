[Compare](https://github.com/oldml/SeerUnityConfig/compare/8c65b8c235dc5e1adfcdb3f15f398f059680e73b...main)

![ConfigPackage](https://img.shields.io/badge/ConfigPackage-20260810115149-blue?style=flat-square)
![DefaultPackage](https://img.shields.io/badge/DefaultPackage-20260810123344-brightgreen?style=flat-square)

> Generated at `2026-08-10 15:01:40 UTC+8` | Branch `main` | Base Commit `8c65b8c`

```diff
! 90 files changed
+ 15,881 insertions(+)
- 325,584 deletions(-)
```

### Created
| Path | Diff (+/-) |
| :--- | :--- |
|  - | `0` |

### Updated
| Path | Diff (+/-) |
| :--- | :--- |
|  [story_1001.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/story_1001.json) | `15,880+ 15,878-` |
|  [profilephoto.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/profilephoto.json) | `1+ 1-` |

### Removed
| Path | Diff (+/-) |
| :--- | :--- |
|  ~[AdventureStory.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/AdventureStory.json)~ | `0+ 212,543-` |
|  ~[twelveYearsPromise.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/twelveYearsPromise.json)~ | `0+ 22,844-` |
|  ~[gainWay.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/gainWay.json)~ | `0+ 19,264-` |
|  ~[side_effect.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/side_effect.json)~ | `0+ 10,121-` |
|  ~[AdventureChapter.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/AdventureChapter.json)~ | `0+ 6,625-` |
|  ~[noHalfPets.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/noHalfPets.json)~ | `0+ 4,164-` |
|  ~[newguideStep2020.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/newguideStep2020.json)~ | `0+ 3,714-` |
|  ~[starmap_temp.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/starmap_temp.json)~ | `0+ 3,047-` |
|  ~[new_starmap.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/new_starmap.json)~ | `0+ 2,586-` |
|  ~[journey_content.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/journey_content.json)~ | `0+ 1,978-` |
|  ~[scene_wildboss.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/scene_wildboss.json)~ | `0+ 1,579-` |
|  ~[Bravechalltask.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Bravechalltask.json)~ | `0+ 1,512-` |
|  ~[Bravecommtask.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Bravecommtask.json)~ | `0+ 1,460-` |
|  ~[elvenkingtrial_exchange.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/elvenkingtrial_exchange.json)~ | `0+ 1,336-` |
|  ~[product_coins.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/product_coins.json)~ | `0+ 918-` |
|  ~[mapdrop.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/mapdrop.json)~ | `0+ 804-` |
|  ~[peakCrusade_levelRules.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/peakCrusade_levelRules.json)~ | `0+ 714-` |
|  ~[pveEnter.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pveEnter.json)~ | `0+ 708-` |
|  ~[chapter_temp.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/chapter_temp.json)~ | `0+ 652-` |
|  ~[LockedSpaceMapConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/LockedSpaceMapConfig.json)~ | `0+ 636-` |
|  ~[tutorial_talk.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/tutorial_talk.json)~ | `0+ 571-` |
|  ~[pass_task.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pass_task.json)~ | `0+ 546-` |
|  ~[LimitUseItemInfo.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/LimitUseItemInfo.json)~ | `0+ 532-` |
|  ~[throw.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/throw.json)~ | `0+ 516-` |
|  ~[LockedSpaceRoomConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/LockedSpaceRoomConfig.json)~ | `0+ 498-` |
|  ~[bottlebonus.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/bottlebonus.json)~ | `0+ 474-` |
|  ~[badgeBattlePass_reward .json](https://github.com/oldml/SeerUnityConfig/blob/main/config/badgeBattlePass_reward%20.json)~ | `0+ 473-` |
|  ~[armorHeroBattlePass_reward.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/armorHeroBattlePass_reward.json)~ | `0+ 444-` |
|  ~[fightTestLevelConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/fightTestLevelConfig.json)~ | `0+ 438-` |
|  ~[awakentask.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/awakentask.json)~ | `0+ 400-` |
|  ~[announcement.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/announcement.json)~ | `0+ 400-` |
|  ~[brave_tower.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/brave_tower.json)~ | `0+ 394-` |
|  ~[fightLabBossConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/fightLabBossConfig.json)~ | `0+ 382-` |
|  ~[ninjaroom.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/ninjaroom.json)~ | `0+ 363-` |
|  ~[ActivityCenter_test.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/ActivityCenter_test.json)~ | `0+ 347-` |
|  ~[Startrekbossconfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/Startrekbossconfig.json)~ | `0+ 316-` |
|  ~[itemsOptimizeCatItem.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItem.json)~ | `0+ 280-` |
|  ~[tutorial_recruitlevel.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/tutorial_recruitlevel.json)~ | `0+ 260-` |
|  ~[BackFlowTask.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/BackFlowTask.json)~ | `0+ 257-` |
|  ~[AdAstraGalaxy_temp.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/AdAstraGalaxy_temp.json)~ | `0+ 256-` |
|  ~[AdAstraGalaxy_guoqing.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/AdAstraGalaxy_guoqing.json)~ | `0+ 256-` |
|  ~[AdAstraGalaxy _temp.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/AdAstraGalaxy%20_temp.json)~ | `0+ 256-` |
|  ~[latestActivity_temp.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/latestActivity_temp.json)~ | `0+ 254-` |
|  ~[journey_level.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/journey_level.json)~ | `0+ 246-` |
|  ~[pvp_MonsterConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pvp_MonsterConfig.json)~ | `0+ 238-` |
|  ~[redbutton.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/redbutton.json)~ | `0+ 222-` |
|  ~[new_starmaplist.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/new_starmaplist.json)~ | `0+ 216-` |
|  ~[awakenlevel.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/awakenlevel.json)~ | `0+ 214-` |
|  ~[pvp_BossConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pvp_BossConfig.json)~ | `0+ 160-` |
|  ~[itemsOptimizeCatItems21.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems21.json)~ | `0+ 148-` |
|  ~[pvp_practice.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/pvp_practice.json)~ | `0+ 141-` |
|  ~[shop_copy.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/shop_copy.json)~ | `0+ 139-` |
|  ~[diamon_task.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/diamon_task.json)~ | `0+ 125-` |
|  ~[natolesJourneyOfRevivalShopConfig.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/natolesJourneyOfRevivalShopConfig.json)~ | `0+ 112-` |
|  ~[h5_12th_box.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/h5_12th_box.json)~ | `0+ 112-` |
|  ~[stg_skill.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/stg_skill.json)~ | `0+ 110-` |
|  ~[error_code_analysis.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/error_code_analysis.json)~ | `0+ 103-` |
|  ~[itemsOptimizeCatItems20.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems20.json)~ | `0+ 100-` |
|  ~[armorHeroBattlePass_task.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/armorHeroBattlePass_task.json)~ | `0+ 88-` |
|  ~[mainLine_chapter.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/mainLine_chapter.json)~ | `0+ 76-` |
|  ~[h5_12th_task.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/h5_12th_task.json)~ | `0+ 76-` |
|  ~[diamon_box.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/diamon_box.json)~ | `0+ 76-` |
|  ~[itemsOptimizeCatItems22.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems22.json)~ | `0+ 70-` |
|  ~[itemsOptimizeCatItems19.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems19.json)~ | `0+ 70-` |
|  ~[learningpower_tower.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/learningpower_tower.json)~ | `0+ 64-` |
|  ~[exp_tower.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/exp_tower.json)~ | `0+ 64-` |
|  ~[aurumEndgameShop.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/aurumEndgameShop.json)~ | `0+ 58-` |
|  ~[toolbar.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/toolbar.json)~ | `0+ 52-` |
|  ~[itemsOptimizeCatItems9.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems9.json)~ | `0+ 52-` |
|  ~[TeamTaskMonsters.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/TeamTaskMonsters.json)~ | `0+ 51-` |
|  ~[monstersOptimizeMonster.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/monstersOptimizeMonster.json)~ | `0+ 49-` |
|  ~[TitleBg.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/TitleBg.json)~ | `0+ 42-` |
|  ~[TeamTasks.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/TeamTasks.json)~ | `0+ 41-` |
|  ~[itemsOptimizeCatItems16.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems16.json)~ | `0+ 40-` |
|  ~[package_update.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/package_update.json)~ | `0+ 34-` |
|  ~[sixteenyearsactpanel.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/sixteenyearsactpanel.json)~ | `0+ 24-` |
|  ~[handbook.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/handbook.json)~ | `0+ 24-` |
|  ~[PreferentialBest.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/PreferentialBest.json)~ | `0+ 24-` |
|  ~[AdAstraShop.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/AdAstraShop.json)~ | `0+ 24-` |
|  ~[exchangeRestrict.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/exchangeRestrict.json)~ | `0+ 21-` |
|  ~[petbookOptimizeMonster.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/petbookOptimizeMonster.json)~ | `0+ 18-` |
|  ~[elGacha.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/elGacha.json)~ | `0+ 14-` |
|  ~[PremiumPetInfo.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/PremiumPetInfo.json)~ | `0+ 14-` |
|  ~[shopbanner.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/shopbanner.json)~ | `0+ 13-` |
|  ~[itemsOptimizeCatItems8.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/itemsOptimizeCatItems8.json)~ | `0+ 10-` |
|  ~[FrameInfo.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/FrameInfo.json)~ | `0+ 10-` |
|  ~[scene_icon.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/scene_icon.json)~ | `0+ 1-` |
|  ~[profilephotoAutoGive.json](https://github.com/oldml/SeerUnityConfig/blob/main/config/profilephotoAutoGive.json)~ | `0+ 1-` |

