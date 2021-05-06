# Freeciv-nations
New nations you can add to Freeciv.


## Imaginary

### Hyborian Age

Nations from Robert E. Howard's Hyborian Era, known from the Conan the Cimmerian stories.

    Aquilonian
    Argossean
    Bossonian
    Brythunian
    Cimmerian
    Corinthian
    Doomite - the followers of Thulsa Doom from the 1982 John Milius movie.
    Gundermen
    Hyperborean
    Kothian
    Nemedian
    Ophirean
    Poitainian
    Stygian
    Taurani
    Turanian
    Zamorian
    Zingaran

### MLP
    
    Crystal Empire
    Griffon
    Pony
    
### Tiberian
    
    Brotherhood of Nod
    Global Defense Initiative
    
### Other

    Ape - Planet of the Apes
    Klackons

## Real-world
    Islamic State
    Romani
    
## Modified default
    Albanian - add Romani as a civilwar_nation.
    American - civilwar_nations to include various Native American nations and state-level subdivisions.
    Australian - add Brotherhood of Nod as a civilwar_nation.
    Bosnia - add Brotherhood of Nod as a civilwar_nation.
    Bulgarian - add Romani as a civilwar_nation.
    Egyptian Arab - add Brotherhood of Nod as a civilwar_nation.
    Iraqi - add the Islamic State as a civilwar_nation.
    Macedonian - add Romani as a civilwar_nation.
    Moldovan - add Romani as a civilwar_nation.
    Montenegrin - add Romani as a civilwar_nation.
    Pictish - add to Thurian group.
    Romanian - add Romani as a civilwar_nation.
    Serbian - add Romani as a civilwar_nation.
    Slovakian - add Romani as a civilwar_nation.
    Soviet - add Brotherhood of Nod as a civilwar_nation.
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

    *include "nation/ape.ruleset"
    *include "nation/aquilonian.ruleset"
    *include "nation/argossean.ruleset"
    *include "nation/bossonian.ruleset"
    *include "nation/brythunian.ruleset"
    *include "nation/cimmerian.ruleset"
    *include "nation/corinthian.ruleset"
    *include "nation/crystal.ruleset"
    *include "nation/doomite.ruleset"
    *include "nation/gdi.ruleset"
    *include "nation/griffon.ruleset"
    *include "nation/gundermen.ruleset"
    *include "nation/hyperborean.ruleset"
    *include "nation/islamicstate.ruleset"
    *include "nation/klackon.ruleset"
    *include "nation/kothian.ruleset"
    *include "nation/nemedian.ruleset"
    *include "nation/nod.ruleset"
    *include "nation/ophirean.ruleset"
    *include "nation/poitainian.ruleset"
    *include "nation/pony.ruleset"
    *include "nation/romani.ruleset"
    *include "nation/stygian.ruleset"
    *include "nation/taurani.ruleset"
    *include "nation/turanian.ruleset"
    *include "nation/zamorian.ruleset"
    *include "nation/zingaran.ruleset"
    
#### …/data/misc/flags.spec

    "f.ape", "flags/ape"
    "f.aquilonian", "flags/aquilonian"
    "f.argossean", "flags/argossean"
    "f.bossonian", "flags/bossonian"
    "f.brythunian", "flags/brythunian"
    "f.cimmerian", "flags/cimmerian"
    "f.corinthian", "flags/corinthian"
    "f.crystal", "flags/crystal"
    "f.doomite", "flags/doomite"
    "f.gdi", "flags/gdi"
    "f.griffon", "flags/griffon"
    "f.gundermen", "flags/gundermen"
    "f.hyperborean", "flags/hyperborean"
    "f.islamicstate", "flags/islamicstate"
    "f.klackon", "flags/klackon"
    "f.kothian", "flags/kothian"
    "f.nemedian", "flags/nemedian"
    "f.nod", "flags/nod"
    "f.ophirean", "flags/ophirean"
    "f.poitainian", "flags/poitainian"
    "f.pony", "flags/pony"
    "f.romani", "flags/romani"
    "f.stygian", "flags/stygian"
    "f.taurani", "flags/taurani"
    "f.turanian", "flags/turanian"
    "f.zamorian", "flags/zamorian"
    "f.zingaran", "flags/zingaran"
    
#### …/data/misc/shields.spec

    "f.shield.ape", "flags/ape-shield"
    "f.shield.aquilonian", "flags/aquilonian-shield"
    "f.shield.argossean", "flags/argossean-shield"
    "f.shield.bossonian", "flags/bossonian-shield"
    "f.shield.brythunian", "flags/brythunian-shield"
    "f.shield.cimmerian", "flags/cimmerian-shield"
    "f.shield.corinthian", "flags/corinthian-shield"
    "f.shield.crystal", "flags/crystal-shield"
    "f.shield.doomite", "flags/doomite-shield"
    "f.shield.gdi", "flags/gdi-shield"
    "f.shield.griffon", "flags/griffon-shield"
    "f.shield.gundermen", "flags/gundermen-shield"
    "f.shield.hyperborean", "flags/hyperborean-shield"
    "f.shield.islamicstate", "flags/islamicstate-shield"
    "f.shield.kothian", "flags/kothian-shield"
    "f.shield.klackon", "flags/klackon-shield"
    "f.shield.nemedian", "flags/nemedian-shield"
    "f.shield.nod", "flags/nod-shield"
    "f.shield.ophirean", "flags/ophirean-shield"
    "f.shield.poitainian", "flags/poitainian-shield"
    "f.shield.pony", "flags/pony-shield"
    "f.shield.romani", "flags/romani-shield"
    "f.shield.stygian", "flags/stygian-shield"
    "f.shield.taurani", "flags/taurani-shield"
    "f.shield.turanian", "flags/turanian-shield"
    "f.shield.zamorian", "flags/zamorian-shield"
    "f.shield.zingaran", "flags/zingaran-shield"
    
#### …/data/misc/flags-large.spec

    "f.ape", "flags/ape-large"
    "f.aquilonian", "flags/aquilonian-large"
    "f.argossean", "flags/argossean-large"
    "f.bossonian", "flags/bossonian-large"
    "f.brythunian", "flags/brythunian-large"
    "f.cimmerian", "flags/cimmerian-large"
    "f.corinthian", "flags/corinthian-large"
    "f.crystal", "flags/crystal-large"
    "f.doomite", "flags/doomite-large"
    "f.gdi", "flags/gdi-large"
    "f.griffon", "flags/griffon-large"
    "f.gundermen", "flags/gundermen-large"
    "f.hyperborean", "flags/hyperborean-large"
    "f.islamicstate", "flags/islamicstate-large"
    "f.kothian", "flags/kothian-large"
    "f.klackon", "flags/klackon-large"
    "f.nemedian", "flags/nemedian-large"
    "f.nod", "flags/nod-large"
    "f.ophirean", "flags/ophirean-large"
    "f.poitainian", "flags/poitainian-large"
    "f.pony", "flags/pony-large"
    "f.romani", "flags/romani-large"
    "f.stygian", "flags/stygian-large"
    "f.taurani", "flags/taurani-large"
    "f.turanian", "flags/turanian-large"
    "f.zamorian", "flags/zamorian-large"
     "f.zingaran", "flags/zingaran-large"
     
#### …/data/misc/shields-large.spec

    "f.shield.ape", "flags/ape-shield-large"
    "f.shield.aquilonian", "flags/aquilonian-shield-large"
    "f.shield.argossean", "flags/argossean-shield-large"
    "f.shield.bossonian", "flags/bossonian-shield-large"
    "f.shield.brythunian", "flags/brythunian-shield-large"
    "f.shield.cimmerian", "flags/cimmerian-shield-large"
    "f.shield.corinthian", "flags/corinthian-shield-large"
    "f.shield.crystal", "flags/crystal-shield-large"
    "f.shield.doomite", "flags/doomite-shield-large"
    "f.shield.gdi", "flags/gdi-shield-large"
    "f.shield.griffon", "flags/griffon-shield-large"
    "f.shield.gundermen", "flags/gundermen-shield-large"
    "f.shield.hyperborean", "flags/hyperborean-shield-large"
    "f.shield.islamicstate", "flags/islamicstate-shield-large"
    "f.shield.kothian", "flags/kothian-shield-large"
    "f.shield.klackon", "flags/klackon-shield-large"
    "f.shield.nemedian", "flags/nemedian-shield-large"
    "f.shield.nod", "flags/nod-shield-large"
    "f.shield.ophirean", "flags/ophirean-shield-large"
    "f.shield.poitainian", "flags/poitainian-shield-large"
    "f.shield.pony", "flags/pony-shield-large"
    "f.shield.romani", "flags/romani-shield-large"
    "f.shield.stygian", "flags/stygian-shield-large"
    "f.shield.taurani", "flags/taurani-shield-large"
    "f.shield.turanian", "flags/turanian-shield-large"
    "f.shield.zamorian", "flags/zamorian-shield-large"
    "f.shield.zingaran", "flags/zingaran-shield-large"
    
