# DG_Mods
Collection of Mods for Cataclysm: Dark Days Ahead

To install, place DracoDogMods folder in your /data/mods/ folder.

### Armoring:
Basic system (will be expanded to have leather, bone, chitin, kevlar and superalloy
options).
You can add or remove armor through crafting menu with Kevlar vest or Kevlar dog
harness (cannot craft yet) and one crated dog. You will have to activate dog
after crafting completed.
Essentially improves health (significantly), adds armor to bash/cut, lowers dodge
(by 1) and speed (mainly by weight, heavier dogs aren't as affected whereas
smaller dogs are affected more heavily).

### Training:
Basic system (will eventually be expanded: either specific training that leads to
"certified" attack dog [train dodge, train special attacks, train melee, etc that
requires sufficient player skill and survival] or incremental stages [partially
trained dog -> semi-trained dog -> nearly-trained dog -> attack dog]).
You need suitable skill (attempting under skill requirements can result in loss
of all items -- including dogs -- there isn't a more complex fail system yet in
CDDA to prevent losing certain items), dog whistle, dog food and crated dog.
Training will take significant time (4 hours, subject to change).
Essentially improves aggression (by 1), damage, dodge (by 1), health (slightly),
morale, speed. May add "LUNGE" attack and/or remove "HIT_AND_RUN" depending on
breed.

### Morale:
Eventually add options to interact with dogs for morale bonuses -- certain breeds
may offer larger bonuses (particularly those with GUILT flag, like Beagle,
Chihuahua, Dachshund) -- to also mimic them more as personal dogs rather than
attack animals.

Changelog:

#### 0.1

- Initial release - can tame and "sleep" labradors.

#### 0.2

- You can now tame and "sleep" all breeds.

- Dog whistle now affects all tamed dogs.

- You can now breed labradors (only normal, not trained attack ones yet).

- You can add or remove armor from tamed labradors or attack labradors.

- You can now train labradors as attack dogs.

#### 0.3

- Added new category 'Animals' with subcategories 'Canine Armor/Breeding/Training'
to control some of the bloat and clogging up normal categories.

- Changed "sleep" to "crated" syntax to improve vocabulary and not be creepy.

- You can now breed attack dogs with untrained dogs or each other and not lose an attack dog.

- You can now attach and remove armor for all dog breeds.

- You can now train all breeds as attack dogs.

- You can now breed all breeds.

- Boxers gain "GROUP_MORALE" and "SWARMS" from new stat calculation.

- All dog breeds have altered "aggression" from new stat calculation.

#### 0.4

- Added new animal control vehicle - contains useful items for pets and rarely may contain a crated dog.

- Corrected a lot of descriptions to better detail what you can do with item as well as fixed the nouns.

- Added new animal shelter location - somewhat frequent as veterinarian clinics with items more geared towards pets. Good location to find rare pets.

- Added new animal pound location - somewhat frequent as veterinarian clinics with items more geared towards pets. Good location to find pets.

- Altered armoring dogs to use tailoring 1 if using Kevlar dog harness, otherwise you can now craft Kevlar dog harnesses by repurposing Kevlar vests.

- Adjusted dog stats.

- Removed breeding due to vanilla breeding ability [no longer manual, but automatic. May want to kennel dogs to replenish supply].

#### 0.4a

- Added CLIMB to qualified dogs that have LEAP.

- Removed breeding explanation from README.

#### 0.4b

- Fix CLIMB flag issue

- Corrected Bulldog to have lunge and attack training description

- Added harvest option to armored dogs for chance to retrieve Kevlar dog harness

#### 0.4c

- Removed obsolete files (some parts are now in vanilla gameplay). May cause issues on first load; should be able to save and reload with no more errors.

- Updated harvest for proper values with recent vanilla changes.