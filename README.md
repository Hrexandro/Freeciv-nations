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

    "f.shield.aquilonian", "flags/aquilonian-shield"
    "f.shield.bossonian", "flags/bossonian-shield"
    "f.shield.doomite", "flags/doomite-shield"
    "f.shield.gunderman", "flags/gunderman-shield"
    "f.shield.kothian", "flags/kothian-shield"
    "f.shield.poitainian", "flags/poitainian-shield"
    "f.shield.pony", "flags/pony-shield"
    "f.shield.stygian", "flags/stygian-shield"
    "f.shield.zamorian", "flags/zamorian-shield"

…/data/misc/flags-large.spec

    "f.aquilonian", "flags/aquilonian-large"
    "f.bossonian", "flags/bossonian-large"
    "f.doomite", "flags/doomite-large"
    "f.gunderman", "flags/gunderman-large"
    "f.kothian", "flags/kothian-large"
    "f.poitainian", "flags/poitainian-large"
    "f.pony", "flags/pony-large"
    "f.stygian", "flags/stygian-large"
    "f.zamorian", "flags/zamorian-large"
…/data/misc/shields-large.spec

    "f.shield.aquilonian", "flags/aquilonian-shield-large"
    "f.shield.bossonian", "flags/bossonian-shield-large"
    "f.shield.doomite", "flags/doomite-shield-large"
    "f.shield.gunderman", "flags/gunderman-shield-large"
    "f.shield.kothian", "flags/kothian-shield-large"
    "f.shield.poitainian", "flags/poitainian-shield-large"
    "f.shield.pony", "flags/pony-shield-large"
    "f.shield.stygian", "flags/stygian-shield-large"
    "f.shield.zamorian", "flags/zamorian-shield-large"
