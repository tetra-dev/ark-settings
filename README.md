# ARKてとら鯖設定情報

身内向けサーバーの設定値です。

設定ファイルに記入している部分以外は紹介を省きます。

また、イベント等に影響して一時的に変更になる場合があります。

PvPモードに関連する記述や動作マップ以外の設定項目も含まれますが、このサーバーはPvEモードかつTheIslandで運営しています。

## Game.ini

>MaxTribeLogs=100

トライブログの保管数は100です。

>bDisableFriendlyFire=False

PvPモードにおいて、フレンドリーファイアが有効です。

>bPvEDisableFriendlyFire=False

PvEモードにおいて、フレンドリーファイアが有効です。

>bDisableLootCrates=False

LootCrate（戦利品）が出現します。

>MaxNumberOfPlayersInTribe=70

トライブの最大規模は70人です。

>bIncreasePvPRespawnInterval=False

PvPモードにおけるリスポーンまでの時間引き延ばしは行っていません。

>bAutoPvETimer=False

PvPモード時にPvEモードに自動的に変更になることはありません。

>bPvEAllowTribeWar=True

PvEモード時、トライブ間で戦争を起こすことを許可しています。

>bPvEAllowTribeWarCancel=False

トライブ間で宣言した戦争をキャンセルすることができます。

>MaxAlliancesPerTribe=10

トライブ1つが参加できる同盟は10個までです。

>MaxTribesPerAlliance=10

同盟は最大で10トライブまでで構成できます。

>bAllowCustomRecipes=True

カスタムレシピを許可しています。

>CustomRecipeEffectivenessMultiplier=1.000000

カスタムレシピアイテムの効果倍率は1倍です。

>CustomRecipeSkillMultiplier=1.000000

カスタムレシピの制作スキルによるボーナス倍率は1倍です。

>bUseCorpseLocator=True

死亡した位置に緑色の光の柱が立ちます。

>bAllowUnlimitedRespecs=False

マインドワイプトニックの使用制限は有効です。

>bAllowPlatformSaddleMultiFloors=False

プラットフォームサドルの複数階化を許可していません。

>SupplyCrateLootQualityMultiplier=2.000000

救援物資のアイテムの品質の倍率は2倍です。

>FishingLootQualityMultiplier=1.000000

釣りのアイテム品質は1倍です。

>UseCorpseLifeSpanMultiplier=1.000000

死体やドロップしたアイテムキャッシュの残存時間倍率は1倍です。（オブジェクトにより異なる時間を持ちます。）

>GlobalPoweredBatteryDurabilityDecreasePerSecond=4.000000

バッテリーの消耗は1秒当たり4です。

>RandomSupplyCratePoints=False

救援物資は決まった位置にスポーンします。

>FuelConsumptionIntervalMultiplier=1.000000

燃料の消費速度倍率は1倍です。

>LimitNonPlayerDroppedItemsRange=0

一定以上プレイヤーから離れた位置のドロップアイテムが残存する距離に制限は設けていません。

>LimitNonPlayerDroppedItemsCount=0

一定以上プレイヤーから離れた位置のドロップアイテムが残存する個数に制限は設けていません。

>bDisableGenesisMissions=False

Genesisにおいてミッションは有効です。

>OverrideMaxExperiencePointsPlayer=53373537

経験値の最大値は53,373,537です。

>PlayerHarvestingDamageMultiplier=1.000000

プレイヤーが収穫物に与えるダメージ倍率は1倍です。これは1アクション辺りの収穫数に影響します。

>CraftingSkillBonusMultiplier=1.000000

制作スキルによるボーナス倍率は1倍です。

>MaxFallSpeedMultiplier=1.000000

最大落下速度の倍率は1倍です。

>OverrideMaxExperiencePointsDino=3550001

恐竜の経験値の最大値は355,001です。

>DinoHarvestingDamageMultiplier=3.000000

恐竜が収穫物に与えるダメージ倍率は3倍です。

>DinoTurretDamageMultiplier=1.000000

恐竜に対するタレットからのダメージの倍率は1倍です。

>MatingIntervalMultiplier=0.100000

交配インターバルは0.1倍です。

>EggHatchSpeedMultiplier=4.800000

孵化速度倍率は4.8倍です。

>BabyMatureSpeedMultiplier=36.799000

恐竜の赤ちゃんの成長速度倍率は36.799倍です。これはローカルマルチプレイのシングルプレイヤー設定に準拠しています。

>BabyFoodConsumptionSpeedMultiplier=1.000000

恐竜の赤ちゃんの食料消費速度倍率は1倍です。

>BabyImprintingStatScaleMultiplier=1.000000

恐竜の赤ちゃんの刷り込みによるステータスボーナス倍率は1倍です。

>BabyCuddleIntervalMultiplier=0.167000

恐竜の赤ちゃんのおねだり要求インターバルは0.167倍です。これはローカルマルチプレイのシングルプレイヤー設定に準拠しています。

>BabyCuddleGracePeriodMultiplier=1.000000

恐竜の赤ちゃんの刷り込み猶予倍率は1倍です。

>BabyCuddleLoseImprintQualitySpeedMultiplier=0.100000

恐竜の赤ちゃんの刷り込み猶予を超過した際の刷り込み品質損失倍率は0.1倍です。

>WildDinoCharacterFoodDrainMultiplier=1.000000

>TamedDinoCharacterFoodDrainMultiplier=1.000000

恐竜の食料消費速度倍率は野生、テイム済み共に1倍です。

>WildDinoTorporDrainMultiplier=1.000000

>TamedDinoTorporDrainMultiplier=1.000000

恐竜の気絶値が下がる速度倍率は野生、テイム済み共に1倍です。

>PassiveTameIntervalMultiplier=1.000000

手渡しテイムのインターバルは1倍です。

>ResourceNoReplenishRadiusPlayers=1.000000

>ResourceNoReplenishRadiusStructures=1.000000

資源のリポップの際の建造物やプレイヤーからの距離倍率は1倍です。

>BaseTemperatureMultiplier=1.000000

基礎気温倍率は1倍です。

>GlobalSpoilingTimeMultiplier=1.000000

肉やベリーの腐敗時間の倍率は1倍です。

>GlobalItemDecompositionTimeMultiplier=1.000000

>GlobalCorpseDecompositionTimeMultiplier=1.000000

死亡時のアイテムや捨てたアイテムの消滅時間の倍率は1倍です。

>CropDecaySpeedMultiplier=1.000000

肥料がない場合の植物の消滅速度倍率は1倍です。

>CropGrowthSpeedMultiplier=1.000000

植物の成長速度倍率は1倍です。

>LayEggIntervalMultiplier=1.000000

恐竜が卵を産むインターバルの倍率は1倍です。

>PoopIntervalMultiplier=1.000000

脱糞のインターバルは1倍です。

>HairGrowthSpeedMultiplier=1.000000

頭髪や顔ひげの伸びる速度倍率は1倍です。

>CraftXPMultiplier=1.000000

>GenericXPMultiplier=1.000000

>HarvestXPMultiplier=1.000000

>KillXPMultiplier=1.000000

>SpecialXPMultiplier=1.000000

経験値取得に関する倍率は一律1倍です。

>StructureDamageRepairCooldown=180

構造物の修理ができるようになるまでに180秒かかります。

>PvPZoneStructureDamageMultiplier=6.000000

PvPエリアにおいて、構造物のダメージ倍率は6倍になります。

>bFlyerPlatformAllowUnalignedDinoBasing=False

ケツァルコアトルのプラットフォームサドルに野生生物は乗りません。

>bPassiveDefensesDamageRiderlessDinos=False

防護柵は騎乗されていない恐竜にダメージを与えません。

>bDisableStructurePlacementCollision=False

構造体の設置衝突判定は有効です。

>bLimitTurretsInRange=False

>bHardLimitTurretsInRange=False

タレットの設置に関する制限はありません。

>bGenesisUseStructuresPreventionVolumes=False

Genesisのミッションエリアでの構造体の設置が可能です。

>PerLevelStatsMultiplier_Player[0]=1.3

>PerLevelStatsMultiplier_Player[1]=1.3

>PerLevelStatsMultiplier_Player[3]=1.3

>PerLevelStatsMultiplier_Player[4]=1.3

>PerLevelStatsMultiplier_Player[5]=1.3

>PerLevelStatsMultiplier_Player[6]=1.3

>PerLevelStatsMultiplier_Player[7]=1.3

>PerLevelStatsMultiplier_Player[8]=1.3

>PerLevelStatsMultiplier_Player[9]=1.3

>PerLevelStatsMultiplier_Player[10]=1.3

>PerLevelStatsMultiplier_Player[11]=1.3

各ステータスのレベルアップ時の上昇倍率は1.3です。


## GameUserSetting.ini

管理に関連する設定は省きます。基本ゲームプレイに影響する部分のみ記載。

>AllowCaveBuildingPvE=True

PvEモードにおいて洞窟内での建築を許可しています。

>EnableExtraStructurePreventionVolumes=False

鉱脈や特定の資源の密集した地域の発生を抑える設定？だと思われます。

このサーバーではこういった鉱脈の類は存在する設定です。

>NoTributeDownloads=True

>PreventUploadSurvivors=True

>PreventUploadItems=True

>PreventUploadDinos=True

>CrossARKAllowForeignDinoDownloads=False

各マップのサバイバーや恐竜の移転を無効化しています。

このサーバーでは複数マップを同時に運営していないので影響なし。

>PreventOfflinePvP=False

オフライン時のPvP攻撃を無効化する設定。無効化していません。殺伐！

>PreventTribeAlliances=False

トライブ同盟は有効です。

>PreventDiseases=False

病気のデバフが有効です。

>NonPermanentDiseases=False

病気と一生付き合っていく可能性があります。

>PreventSpawnAnimations=False

リスポーン時の腕を見るアニメーションが有効です。

>OxygenSwimSpeedStatMultiplier=1.000000

酸素消費倍率は1倍です。

>TribeNameChangeCooldown=15

トライブの名称変更時、再度変更になるまでに15分を要します。

>AllowTekSuitPowersInGenesis=False

Genesisにおいて、Tekスーツの着用が禁じられるエリアがあります。

>globalVoiceChat=False

ゲーム内ボイスチャットは無効です。（Discord使用のため）

>proximityChat=False

近接チャットは無効です。（ローカル）

>alwaysNotifyPlayerLeft=True

>alwaysNotifyPlayerJoined=True

ログイン、ログアウト通知が有効です。

>ServerCrosshair=True

サーバーのクロスヘア（火器類使用時に出てくる照準）は有効です。

>AllowThirdPersonPlayer=True

3人称視点が可能です。

>ShowMapPlayerLocation=True

マップに自分の位置が出ます。

>EnablePVPGamma=True

>DisablePvEGamma=False

ガンマ値設定が変更できます。

>ShowFloatingDamageText=True

与えたダメージのフライテキストが表示されます。

>AllowHitMarkers=True

遠距離武器がヒットした際にクロスヘアが赤くなります。

>AllowFlyerCarryPVE=True

PvEモード時、飛行恐竜がほかの恐竜やプレイヤーをつかめます。

>PlayerCharacterWaterDrainMultiplier=0.500000

>PlayerCharacterFoodDrainMultiplier=0.500000

プレイヤーの食料や水の消費倍率は1倍です。

>TamedDinoDamageMultiplier=1.000000

>TamedDinoResistanceMultiplier=1.000000

テイム済み恐竜のダメージ・被ダメージ倍率は1倍です。

>MaxTamedDinos=10000

サーバー内のテイム済み恐竜の最大値は10,000です。

>AllowRaidDinoFeeding=False

レイド恐竜（ティタノサウルス）は食料を得ることができません。（時間経過で必ず死にます）

>RaidDinoCharacterFoodDrainMultiplier=1.000000

また、レイド恐竜の食料の消費速度は1倍です。

>DisableDinoDecayPvE=True

>PvPDinoDecay=False

>AutoDestroyDecayedDinos=False

>PvEDinoDecayPeriodMultiplier=1.000000

しばらくログインしなかった場合のテイム済み恐竜の減衰はありません。

また、仮に減衰したとしても勝手には消滅しません。

>MaxPersonalTamedDinos=4000.000000

個人がテイムできる恐竜の数は最大4,000です。

>PersonalTamedDinosSaddleStructureCost=19

プラットフォームサドルはテイム済み恐竜19体に相当します。

>DisableImprintDinoBuff=False

刷り込みバフは有効です。

>AllowAnyoneBabyImprintCuddle=False

刷り込み主以外の刷り込みはできません。

>TamingSpeedMultiplier=10.000000

テイム速度は10倍です。

>DisableWeatherFog=True

霧は無効化されています。

>PvPStructureDecay=False

PvPモード時の構造物の自然消滅はありません。

>TheMaxStructuresInRange=10500.000000

一定範囲に設置できる構造物は10,500ユニットまでです。

>PerPlatformMaxStructuresMultiplier=1.000000

プラットフォーム上の構造体の設置倍率は1倍です。

>MaxPlatformSaddleStructureLimit=50

プラットフォームサドル上の構造体の数は50までです。

>OverrideStructurePlatformPrevention=False

プラットフォームの上ではタレットやスパイクが機能しません。

>PvEAllowStructuresAtSupplyDrops=False

構造体は救援物資の落下地点には設置できません。

>DisableStructureDecayPVE=True

>AutoDestroyOldStructuresMultiplier=0.000000

PvEモード時、構造体は自然消滅しません。

>ForceAllStructureLocking=False

明示的に設定しなければ構造体はロックされません。

>DestroyUnconnectedWaterPipes=False

水道管はつながっていない場合でも壊れません。

>AlwaysAllowStructurePickup=False

>StructurePickupTimeAfterPlacement=30.000000

>StructurePickupHoldDuration=0.500000

構造体は回収可能になるまでに設置から30秒掛かります。また、ホイールメニューで0.5秒ホールドする必要があります。

>ItemStackSizeMultiplier=1.000000

アイテムスタック数の倍率は1倍です。

>StructurePreventResourceRadiusMultiplier=1.000000

構造体は周辺の資源のスポーンを抑制しますが、影響する距離倍率は1倍です。

>PlatformSaddleBuildAreaBoundsMultiplier=1.000000

プラットフォームサドルの建築制限倍率は1倍です。

>KickIdlePlayersPeriod=3600.000000

放置プレイヤーは3,600秒でキックされます。

>OverrideOfficialDifficulty=5.0

野生恐竜の出現レベルが5倍になっています。

>MaxPlayers=70

最大同時接続数は70です。
