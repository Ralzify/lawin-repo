# How to Use

- Open your Backend file, and find the file called "DefaultGame.ini" (typically in CloudStorage folder)
- At the bottom, where there is nothing, make a new line with the text "[AssetHotfix]". Then go one more line down and paste these.

# Health

- Remove Mini Shield Cap: 
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.ShieldSmallCap;0;100

- Modify Mini Shield Heal Amount: 
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.ShieldSmallAmount;0;100

- Modify Mini Shield Stack Amount: 
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.Consumables.MaxStackAmount.SmallShield;0;10

- Modify Big Potion Heal Amount: 
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.ShieldPotion.ShieldHealAmount;0;100

- Modify Slurp Juice Health Per Tick: 
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.PurpleStuff.EffectiveHealthPerTick;0;25

- Remove Bandage Cap: 
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.Bandage.HealCap;0;1

- Modify Bandage Heal Amount: 
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.Bandage.HealAmount;0;25

- Modify Chug Splash Heal Amount: 
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.ChillBronco.MaxHeal;0;100

- Modify Flopper Heal Amount:
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.Flopper.Heal;0;50

- Modify Slurp Fish Heal Amount:
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.FlopperEffective.Heal;0;50

- Modify Deadpool Dualies Heal Amount: 
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.Donut.LifeStealMult;0;0.3


# Materials

- Modify Wood Stack Amount: 
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.MaxStack.Resources.Wood;0;5000

- Modify Brick Stack Amount: 
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.MaxStack.Resources.Stone;0;5000

- Modify Metal Stack Amount: 
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.MaxStack.Resources.Metal;0;5000

# Vehicles
- Currently, they are all set to 0, meaning it will disable them if put in the backend. If you want to enable them on other seasons that may not have them, then change the second 0 to a 100.

- Hoverboard Spawn Percent:
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.HoverBoard.MinSpawnPercent;0;0
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.HoverBoard.MaxSpawnPercent;0;0

- Quadcrasher Spawn Percent:
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.QuadBike.MinSpawnPercent;0;0
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.QuadBike.MaxSpawnPercent;0;0

- Shopping Cart Spawn Percent:
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.ShoppingCart.MinSpawnPercent;0;0
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.ShoppingCart.MaxSpawnPercent;0;0

- ATK Spawn Percent:
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.GolfCart.MinSpawnPercent;0;0
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.GolfCart.MaxSpawnPercent;0;0

- Plane Spawn Percent:
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.BiPlane.MinSpawnPercent;0;0
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.BiPlane.MaxSpawnPercent;0;0

- Baller Spawn Percent:
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.HamsterBall.MinSpawnPercent;0;0
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.HamsterBall.MaxSpawnPercent;0;0

- Cannon Spawn Percent:
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.Cannon.MinSpawnPercent;0;0
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.Cannon.MaxSpawnPercent;0;0

- Boat Spawn Percent:
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.Boat.MinSpawnPercent;0;0
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.Boat.MaxSpawnPercent;0;0

- Season 13 Cars Spawn Percent:
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.Valet.MinSpawnPercent;0;0
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.Valet.MaxSpawnPercent;0;0

- Choppa Spawn Percent:
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.Choppa.MinSpawnPercent;0;0
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.Choppa.MaxSpawnPercent;0;0

# Consumable Send/Launch Distance, Momentum & Gravity

- Modify Impulse Momentum: 
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.KnockGrenade.LaunchVelocity;0;10000

- Modify Impulse Vehichle Momentum: 
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.KnockGrenade.LaunchVelocity.Vehicle;0;10000

- Modify Shockwave Momentum: 
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.ShockwaveGrenade.LaunchVelocity;0;10000

- Modify Chiller Momentum: 
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.IceGrenade.LaunchVelocity;0;8000

- Modify Chiller Walk Speed: 
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.IceGrenade.WalkSpeedMultiplier;0;8000

- Modify Flint-Knock Momentum: 
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.PistolFlintlock.KnockMagSelf;0;8000

- Modify Dub Momentum: 
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.Dub.KnockMagSelf;0;8000

- Modify Launch Pad Momentum: 
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.Launchpad.LaunchStrength;0;10000

- Modify Crash Pad Horizontal Launch: 
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.AppleSun.LaunchVelocity.HorizontalLaunch;0;20000

- Modify Chug Splash Gravity: 
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.GravityScale.ChugSplash;0;0

- Modify Chug Splash Speed: 
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.Projectile.Speed.ChugSplash;0;5000

- Modify Floor Bouncer Momentum: 
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.BouncePad.Floor.Player.MaxVelocity;0;6000

- Modify Vehicle Floor Bouncer Momentum:
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.BouncePad.Floor.Vehicle.MaxLateralVelocity;0;6000

- Modify Wall Bouncer Momentum: 
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.BouncePad.Wall.Player.MaxLateralVelocity;0;6000

- Modify Vehicle Wall Bouncer Momentum:
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.BouncePad.Wall.Vehicle.MaxLateralVelocity;0;6000

- Modify Grappler Distance (how long it can last): 
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.HookGun.ProjectileLifespan;0;50

- Modify Jules' Grappler Distance (how long it can last): 
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.GrapplingHoot.ProjectileLifespan;0;50

- Modify Jules' Grappler Vehichle Force: 
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.GrapplingHoot.VehicleForceMultiplier;0;10000

- Modify Batman's Grapnel Gun Distance (how long it can last, only works on LawinV2 & Momentum): 
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.BadgerGrape.ProjectileLifespan;0;50

- Modify Boogie Bomb Jump Multiplier: 
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.DanceGrenade.JumpMultiplier;0;6

- Modify Rusty Can's Gravity: 
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.BucketOld.Grav;0;0

- Modify Rusty Can's Speed: 
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.BucketOld.Speed;0;10000

- Modify Mythic Goldfish's Gravity: 
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.BucketNice.Grav;0;0

- Modify Mythic Goldfish's Speed: 
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.BucketNice.Speed;0;10000

- Modify Stink Bomb Gravity: 
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.Default.GravityScale.Stink;0;0

- Modify Cube Low Gravity: 
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.Cube.Lowgrav;0;5

- Modify Cube Send Amount: 
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.Cube.Impulseamount;0;15000

- Modify Junk Rift's Speed: 
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.Projectile.Speed.JunkRift;0;6000

- Modify Stink Bomb's Speed: 
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.Projectile.Speed.StinkBomb;0;6000

- Modify Glider Redeploy Speed: 
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.ParachuteControlGliderRedeploy.MaxLateralSpeed;0;4000

- Modify Zipline Speed: 
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.ZipLine.Speed;0;4000

- Modify Hop Flopper Low Gravity Duration:
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.HopFlopper.Duration;0;999999999999

- Modify Witch Broom Launch Amount:
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.WitchBroom.VerticalLaunchMagnitude;0;8000
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.WitchBroom.HorizontalLaunchMagnitude;0;8000

- Modify Grenade Launcher Gravity:
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.GrenadeLauncher.Projectile.Gravity;0;0.4 // S19 GL

- Modify Grenade Launcher Speed:
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.GrenadeLauncher.Projectile.Speed;0;4500.0 // S19 GL

- Modify Knee Sliding Maximum Speed/Velocity:
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.Sliding.MaxLateralSlidingSpeed;0;400

# Game Settings

- Glider Redeploy (0 for no, 1 for yes): 
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.GliderRedeploy.CanRedeploy;0;1

- Disable C2S5 Sand: 
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.Sand.Enabled;0;0

- Disable Sliding:
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.Sliding.Enabled;0;0

- Allow Everyone to Edit Each Other's Walls: 
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;AllowNeutralEditing;0;1

- Modify Crash Pad Lifespan: 
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.AppleSun.Lifespan;0;99999999999999

- Disable Jules' Grappler Glider Redeploy: 
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.GrapplingHoot.DisableGliderDeploy;0;1

- Modify Stink Bomb Damage: (I swear this is a datatable thing but whatever)
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.StinkBomb.PlayerDamage;0;25

- Modify Stink Bomb Duration: 
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.GasGrenade.GasDuration;0;0

- Modify Boogie Bomb Duration:
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.DanceGrenade.Duration;0;100

- Modify Rift-to-Go Active Duration:
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.Rift.Item.ActiveDuration;0;99999999999999

- Enable/Disable Free Vending Machines:
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.VendingMachine.ItemsAreFree;0;0

- Disable Shockwave Box Exploiting (Shockwaves break player builds)
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.ShockwaveGrenade.ShouldDestroyStructure;0;0

- Disable Crashpad Box Exploiting (Crashpad break player builds)
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.AppleSun.EnvironmentDamage;0;0

- Modify Boogie Bomb Stack Amount: (you can also change the BoogieBomb to be basically any consumable, ie: ShockwaveGrenade, Chugsplash, etc)
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.Consumables.MaxStackAmount.BoogieBomb;0;4

- Modify Boom Sniper Rifle Damage on Hit:
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.BoomSniper.DamageOnHit;0;157

- Change Turbo Build Rate:
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.TurboBuildInterval;0;0.002

# Fixes

- Fix Season 16+ Ammo Count Cap:
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.Ammo.MaxStackAmount.Shells;0;999
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.Ammo.MaxStackAmount.Light;0;999
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.Ammo.MaxStackAmount.Medium;0;999
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.Ammo.MaxStackAmount.Heavy;0;999

- Fix Gold Cap:
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.ResourceWadCap;0;10000

- Fix S19 Lategame Storm Damage:
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.SafeZone.Damage;0;0

# Extra

- If someone can figure out how to use this to unvault an item, that would be insane.
+CurveTable=/Game/Athena/Balance/DataTables/AthenaGameData;RowUpdate;Default.Item.Unvaulted;0;0?

- (untested) Change the name of the running game task?

[/Script/EngineSettings.GeneralProjectSettings]
ProjectID=(A=-2011270876,B=1182903154,C=-965786730,D=-1399474123)
ProjectName=Ralzify
ProjectDisplayedTitle=NSLOCTEXT("", "FortniteMainWindowTitle", "Ralzify")
ProjectVersion=1.0.0

- Double Pump for everyone without using DataTables (NOTE: Put in DefaultEngine.ini)

[ConsoleVariables]
Weapon.TryToFireRestrictedByTypeCooldowns=0

- Straight Bloom For All Guns: (NOTE: Put in DefaultEngine.ini)

[/Script/FortniteGame.FortBaseWeaponStats]
Spread=0
