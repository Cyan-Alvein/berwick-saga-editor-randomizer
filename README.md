# Berwick Saga Editor & Randomizer

## How to Patch a Berwick Saga Rom with Command Line:

Run ```python3 BWSISOEditor.py BerwickSagaRom.iso PatchedRom.iso YourScript.txt [-jp] [-en]``` on your terminal.

By default we use Aethin's english translation, you can specify ```-jp``` to modify the japanese rom.

## How to Patch a Berwick Saga Rom with the GUI Editor:
Run  ```python3 EditorTK.py```

## How to use the Randomizer:
Run  ```python3 RandomizerTK.py```

After obtaining the randomized script, use the editor to patch your rom.

## My script, the only file I added in this project
I create the script "BWS_Lunatic Cyan"
It took me more than 4 months to made this, fixing all bugs, testing all possibilities by replaying the patched games many times (Yeah I love this game too much), managing character balances so someone (Faye Dean Ruby Derrick...) aren't too OP

If you wanna tip me:
My monero address is: 87totSvhKggX9E14sC5dAu2Rb9X5nEEiZPCJHGUsPgLU65RjixyB7uMcxpq4ATNcM77qQa3s8QimNYHvd6uAgScwNmZG3Fo
My bitcoin address is: bc1q3e0knh6kahwgmwt4jjs4xw7l5sx452zsz8vyvv
If you wanna contact me:
Simplex Address: https://simplex.chat/contact#/?v=2-7&smp=smp%3A%2F%2Fh--vW7ZSkXPeOUpfxlFGgauQmXNFOzGoizak7Ult7cw%3D%40smp15.simplex.im%2FQ7pGQDFZgl6wyjhJToF-IV0r6Yp5mjz0%23%2F%3Fv%3D1-3%26dh%3DMCowBQYDK2VuAyEA_yFMi-B0MDEb2PZPnPC2qX6o86wks29AyoHCZO6Ej34%253D%26srv%3Doauu4bgijybyhczbnxtlggo6hiubahmeutaqineuyy23aojpih3dajad.onion
Gmail Address: Cyan.Alvein@gmail.com
My Twitter Account: https://x.com/GlennFrost15
My Nosttr Account: https://nostter.app/nprofile1qqs8486svgm5dgret9gr3xamkgkj9mudy6cpzzha9ug9g6l205tklvgpuuyn3

## What I changed in the games
 pitchfork & MilitaryFork got cripple-rate *4
 Pike & holy & BastardSword got cripple-rate *6
 AirKnife got injure-rate 30, so it is a bolt, try to steal it early
 All weapon & magic regenerate, so use them at will
 Everyone got Mercy, Deathmatch, Canto, Adept, Sunder, Windsweep, BattleCry, Pulverize, Flourish (If you can equip Blade or Axe) Skill
 All ennemy got huge amount of skill too + Supporter to increase their hit rate and crit (The game refuse to increase their hit rate with base sword +10 and stuff (Yeah even deathmatch, Good luck vs a Chaos with Deathmatch, Critical, Adept, Pursuit, Parry aka all Volo skill without Astra - May the best win)
 The game only show 2 screen for skill, All the skill work fine, even those which the game doesn't show up
 All prefered & many rare weapon got slower weapon weapon rank, so Kramer can use Brymranger at level 15, Saphira can use Rehabilitate at level 15 ...
 Sword user without shield got pursuit skill (Faye Kramer Volo Faramir ) & Dean too since for him his axes are his sword :)
 All axes users got Vengeful skill, Axel and his class type ( Corsair - Barbarian - Pirate ) are the only one with both vengeful & Counter skill
 All player characters got +20 base weapon skill, so don't waste your time trying to farm Weapon EEXP, just play and enjoy the game.
 All unpromoted player class weapon cap are set as promoted class weapon cap. So Sherlock can reach bow rank 60 without getting promoted
 If you want Leon & Adel or even ruby to use lance, just type this code Set Ruby Skill Lance, I tested it and it worked. But don't activate the skill desperation while attacking with lance, it will work but that is cheating xD. The battle animation will be bugged to, same for faramir astra, so fight without battle animation in those case.
 Accessories item got huge buff, SpiritBrace = Magic +2, BlessedBrace  = Magic +4 Speed -2, DivineBrace (Aegina own it)= Magic +6 Defense -2 Speed -2
 TigerBrace = Hit +15 Avoid -10, EagleBrace = Unchanged, GuardBrace = Defense +2, FeatherBrace = Speed +2. You get the idea
 All magic weapon (Exept Dark) got +1 range, so AirBlade = 2 range, DireThunder = 3 range
 All healing weapon got +2 range, so heal = 3 range, Physic = 5 range (same as Darkmend, It pissed me off a dark healing magic was > than a holy healing magic. WTF Shogo Kaga)
 Airblade, Windstorm, PallasRiana all got 6 injure-rate, Blizzard got 80 injure-rate. Thief unit like Czene and Thaddy with their Bolt and pursuit skill deal >= 60% injure-rate. I made this change to balance Thief and Mage injure-rate
 Fire got 12 injure-rate, Hellfire = 18 injure-rate, PallasLeia = 24 injure-rate. The goal here is to make that using wind & fire magic inflict the same amount of injure-rate
 Thunder and DireThunder = 2 cripple-rate, PallasLeia = 8 cripple-rate. I am not really sure how cripple-rate function here works. I made this change by considering the function cripple-rate 6 = Apeiron effect in game.
 All prefered weapong rank are now <= 20. So Thaddy can use AssassinsKnife at level 20, Ruby can use Perseid at level 20, Volo can use Brymranger at level 20
 Special weapon like RazeEtoile Vollenden Drakelance are available very early in the game, and they all got restore-uses effect, so don't hesitate to abuse them. You will need it since Ennemy are too OP now.
 Marcel, General class got protector
 All priest class got resistor skill, yes even Izerna & ennemy priest
 Sherpa & Adel got swordbane - Arthur & Paramythis got Spearbane - Axel & Ruby got Axebane
 No one force you to use the Deathmatch skill in the game, it will make the game easy. It is there mainly to allow you to create epic fight vs boss. Normally I will only only Myrmidon, Axefighter, Assassin and Spearknight to use it ( Faye Volo Faramir Dean Leon Adel Czene Thaddy )
 The function "learned" bug too much, instead of learning overwatch, someone can learn the skill "silence" instead. So I never used "learned" 