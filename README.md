# weaponMaker

## Use Guide:

### Weapon ID
Non-decimal integer, cannot be used by another weapon

### Weapon Name
String

### Rarity
Integer from 0-MAXTIER.

### Type
Determines ammo type, 0 being gun ammo and 1 being mana

### Damage
Decimal, damage of starting pistol is 1.

### Shots per second
Decimal, firerate of starting pistol is 5.5.

### Knockback
Decimal, knockback of starting pistol is 2. Reccomended maximum of 4, 0 is acceptable as no knockback.

### Inaccuracy
Decimal, in degrees; i.e. inaccuracy of 10 gives an angle that can be up to 10 less or 10 more than initial shot angle.

### Projectile Speeds
Decimal, number of pixels travelled by projectile per frame; starting pistol is 15.2. Set both min/max to same value for no deviation.

### Shot type:
Integer to represent shottypes. So far shottypes are:
0 = normal shot,
1 = shotgun

### Element:
Integer, so far are:
0 = none,
1 = fire,
2 = ice,
3 = electric

### Extras
Depends on the given shottype. 
0 = NO ARGUMENTS
1 = Number of projectiles,n/a,n/a
