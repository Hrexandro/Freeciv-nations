# Freeciv-nations
New nations you can add to Freeciv.


## Imaginary

### Hyborian Age

Nations from Robert E. Howard's Hyborian Era, known from the Conan the Cimmerian stories. Their civilwar_nations include neighbours, subnations, as well as the real-world peoples that inspired or are supposed descendants of a given nation.

    Aquilonian
    Bossonian
    Doomite - the followers of Thulsa Doom from the 1982 John Milius movie.
    Gundermen
    Kothian
    Poitainian
    Stygian
    Zamorian

### MLP

    Pony

## Real-world
    Islamic State
    Romani
    
## Modified default
    Albanian - add Romani as a civilwar_nation.
    American - civilwar_nations to include various Native American nations and state-level subdivisions.
    Bulgarian - add Romani as a civilwar_nation.
    Iraqi - add the Islamic State as a civilwar_nation.
    Macedonian - add Romani as a civilwar_nation.
    Moldovan - add Romani as a civilwar_nation.
    Montenegrin - add Romani as a civilwar_nation.
    Pictish - add to Thurian group.
    Romanian - add Romani as a civilwar_nation.
    Serbian - add Romani as a civilwar_nation.
    Slovakian - add Romani as a civilwar_nation.
    Syrian - add the Islamic State as a civilwar_nation.
    Turkish - add Romani as a civilwar_nation.
    

# Installation

Put the folders inside your Freeciv folder and merge with existing directories. Paste the following lines to the files below:

#### …/data/default/nationlist.ruleset

###### Under ngroups:

    [ngroup_thurian]
    name=_("?nationgroup:Thurian")
    match=3
    [ngroup_future]
    name=_("?nationgroup:Future")
    match=2
    [ngroup_equestrian]
    name=_("?nationgroup:Equestrian")
    match=2

###### At the bottom:

    *include "nation/aquilonian.ruleset"
    *include "nation/bossonian.ruleset"
    *include "nation/doomite.ruleset"
    *include "nation/gundermen.ruleset"
    *include "nation/islamicstate.ruleset"
    *include "nation/kothian.ruleset"
    *include "nation/poitainian.ruleset"
    *include "nation/pony.ruleset"
    *include "nation/romani.ruleset"
    *include "nation/stygian.ruleset"
    *include "nation/zamorian.ruleset"

#### …/data/misc/flags.spec

    "f.aquilonian", "flags/aquilonian"
    "f.bossonian", "flags/bossonian"
    "f.doomite", "flags/doomite"
    "f.gundermen", "flags/gundermen"
    "f.islamicstate", "flags/islamicstate"
    "f.kothian", "flags/kothian"
    "f.poitainian", "flags/poitainian"
    "f.pony", "flags/pony"
    "f.romani", "flags/romani"
    "f.stygian", "flags/stygian"
    "f.zamorian", "flags/zamorian"
      
#### …/data/misc/shields.spec

    "f.shield.aquilonian", "flags/aquilonian-shield"
    "f.shield.bossonian", "flags/bossonian-shield"
    "f.shield.doomite", "flags/doomite-shield"
    "f.shield.gundermen", "flags/gundermen-shield"
    "f.shield.islamicstate", "flags/islamicstate-shield"
    "f.shield.kothian", "flags/kothian-shield"
    "f.shield.poitainian", "flags/poitainian-shield"
    "f.shield.pony", "flags/pony-shield"
    "f.shield.romani", "flags/romani-shield"
    "f.shield.stygian", "flags/stygian-shield"
    "f.shield.zamorian", "flags/zamorian-shield"

#### …/data/misc/flags-large.spec

    "f.aquilonian", "flags/aquilonian-large"
    "f.bossonian", "flags/bossonian-large"
    "f.doomite", "flags/doomite-large"
    "f.gundermen", "flags/gundermen-large"
    "f.kothian", "flags/kothian-large"
    "f.islamicstate", "flags/islamicstate-large"
    "f.poitainian", "flags/poitainian-large"
    "f.pony", "flags/pony-large"
    "f.romani", "flags/romani-large"
    "f.stygian", "flags/stygian-large"
    "f.zamorian", "flags/zamorian-large"
#### …/data/misc/shields-large.spec

    "f.shield.aquilonian", "flags/aquilonian-shield-large"
    "f.shield.bossonian", "flags/bossonian-shield-large"
    "f.shield.doomite", "flags/doomite-shield-large"
    "f.shield.gundermen", "flags/gundermen-shield-large"
    "f.shield.islamicstate", "flags/islamicstate-shield-large"
    "f.shield.kothian", "flags/kothian-shield-large"
    "f.shield.poitainian", "flags/poitainian-shield-large"
    "f.shield.pony", "flags/pony-shield-large"
    "f.shield.romani", "flags/romani-shield-large"
    "f.shield.stygian", "flags/stygian-shield-large"
    "f.shield.zamorian", "flags/zamorian-shield-large"
    
