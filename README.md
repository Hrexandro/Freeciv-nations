# Freeciv-nations
New nations you can add to Freeciv.


## Imaginary

### Hyborian Age

Nations from Robert E. Howard's Hyborian Era, known from the Conan the Cimmerian stories. Their civilwar_nations include neighbours, subnations, as well as the real-world peoples that inspired or are supposed descendants of a given nation.

    Aquilonian

    Bossonian

    Doomite - Included are the followers of Thulsa Doom from the 1982 John Milius movie.

    Gundermen

    Kothian

    Poitainian

    Stygian

    Zamorian

### Other

    Pony

## Real-world

    American - civilwar_nations to include various Native American nations and state-level subdivisions (Californian, Texan, Vermont).

# Installation

Put the folders inside your Freeciv folder and merge with existing directories. Paste the following lines to the files below:

#### …/data/default/nationlist.ruleset
    *include "nation/aquilonian.ruleset"

    *include "nation/bossonian.ruleset"

    *include "nation/doomite.ruleset"

    *include "nation/gundermen.ruleset"

    *include "nation/kothian.ruleset"

    *include "nation/poitainian.ruleset"

    *include "nation/pony.ruleset"

    *include "nation/stygian.ruleset"

    *include "nation/zamorian.ruleset"

…/data/misc/flags.spec

		"f.aquilonian", "flags/aquilonian"
      
		"f.bossonian", "flags/bossonian"
      
		"f.doomite", "flags/doomite"
      
		"f.gunderman", "flags/gunderman"
      
		"f.kothian", "flags/kothian"
      
		"f.poitainian", "flags/poitainian"
      
		"f.pony", "flags/pony"
      
		"f.stygian", "flags/stygian"
      
		"f.zamorian", "flags/zamorian"
      
…/data/misc/shields.spec

…/data/misc/flags-large.spec

…/data/misc/shields-large.spec
