#Project Cohen

This is an RPG game that is a bit dungeon hack and slash, 2d WoW clone
with a city building component. The overall idea is that you'd start out
as a young adventurer in a small town that makes a name for themselves
by going on adventures and saving people and collecting loot. As you
amass your fortunes you can build out your house. Eventually you get
promoted as the leader of your town. Once you've become the leader you
can start more ambitious projects like building a library or university.
Building up defenses and barraks. In an as of yet undefined relationship
as you build out your city you become more powerful and receive bonuses
from the city.

The city building part is still quite undefined and I've not yet thought
how to make it meaningfully important to the character and their
adventures. The rpg part is a bit more defined. Players will be able to
choose from three classes, mostly defined by their play style. Warrior -
melee fighter, Wizard - range fighter, relies on combinations of spells
to destroy enemies, Rangers - range fighter that are also sneaky and can
open up fights in melee range. After a certain amount of levels players
would be able to augment their class. For example a Wizard could pick up
warrior skills to become a Battle Mage or a ranger can become an
assassin that can sneak up on nearly anything. Warriors would be able to
become paladins(or knight) getting blessings from their gods, or a Mage
Knight which let the warrior cast spells that enhance their melee
weapons and attacks. The exact flow and different options are to be
determined. One idea is also allow Grand Wizards and Warlords which
would be as if the player chose not to augment their class but continue
increasing their skill in their chosen class.

One thing I'd want to abandon up front is the idea of balance. Classes
should be varied in play style but not necessarily balanced. Ideally any
class can complete any quest, but it is okay if a Ranger is more
difficult to have success with than say a Warrior.

##Classes

As I mentioned before, initially I'd want to aim to have 3 classes:
Wizard, Warrior and Ranger(this one may change)

###Warriors

Warriors are skilled in melee combat. They have little fear of getting
close to an enemy and facing them eye to eye. Warriors would be able to
use two hand weapons or a sword and a shield. Using a shield should not
necessarily mean that a warrior does less damage than a two hand weapon,
but it will mean there will be different skills the warrior will rely on

###Wizards

Wizards have to be crafty. They're weak at close range, though they are
still very good with a staff. They often time will use spells or a
combination of spells to defeat enemies. I think spell combinations
could be a fun mechanic for wizards. Think of it like this, the wizard
casts a poison cloud on a monster, and then launches a firebolt. The
fire causes the poison cloud to ignite doing more damage than the poison
cloud or the firebolt alone. 

###Rangers

Rangers are trained to be silent killers, they enjoy shooting from the
shadows though if they can get close to an enemy they will have several
options to  hinder the enemy. A few ideas are, a ranger sneaks up on a
enemy and gives them a tremendous kick, this kick knocks the enemy
some distance away giving the ranger time to shoot some arrows at the
enemy. The ranger could also temporarily incapcitate the enemy (blind or
daze them with powder). I think with this class it could be easy to get
boring so we'd need to come up with some pretty clever skills.

##Starting the game

One idea I'd like to explore is that when the user begins a game they
are classless, and through choices in the game they choose what class
they want. I think because of this we'd have to a common set of skills
for each class. So each class would need to be able to have some
competentcy in melee combat, and some other base skills probably. But
after a brief tutorial the player will have to make a decision on which
class they want to play as. This will most likely be the first real
quest (and might be skippable in future replays). 

##Combat

I want to explore both realtime combat and turn based. Initially I will
work on realtime combat. This means players attack when they can and can
use their abilities whenever the abilities are ready. The world might be
based off of tiles, but movement will be free form (meaning a player can
be partially in a tile) If I must go the turn based route, it will be
similar to combat in Avadon where once the user is within range of an
enemy they are put into combat mode. This style of play might greatly
advantage rangers since they would have more control of when they get
put into combat mode due to their stealthiness.

##To Do List
* Make a basic movement prototype in python
* Add in user actions (think about how to easily add new actions in the
  future)
* Add in some baddies for the user to kill
* Think about how combat will work, what are the modifiers to combat?
  How does attacking and damage work?
* Play with the prototype long enough until we can start getting a feel
  for the above.
