# Mix'n'Match
## The general purpose gameplay mod combiner

This is a work in progress and some features may be incomplete.

### What the hell is this thing?

This mod allows one to merge any gameplay mods that replace items, monsters and
various others into randomized replacement pools. It also has the option of
re-adding vanilla things into the mix.

### The options

By default, the mod will make pools for monsters and items, but there are
some lil' on/off switches to tweak this, separated in "Weapons/Ammo",
"Monsters", "Items" and "Everything Else". The option to add vanilla stuff to
the pool is also there. Other than that, that's pretty much all there is to
configure.

Well, there's also the option to respect or not the "IsFinal" flag for
zscript-based replacements. Keep in mind that many mods may have important
reasons to use this flag.

### Caveats

Currently, weapons that are assigned to slots through any method other than the
SlotNumber property, aren't supported. Workarounds for this will be attempted
eventually.
