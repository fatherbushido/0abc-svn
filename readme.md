# 0 A.D. Available Balance Changes
This mod bundles multiple gameplay balance and organizatorial tweaks for the current development version of *0 A.D. “Empires Ascendant”*. Although there are multiple gameplay mods available already, the approach of this one is different. Each change has its own patch available on (https://code.wildfiregames.com/)[phabricator], to make it easier for team members to discuss, play-test, and commit them.

## Table of Contents
* [Gameplay and balance tweaks](https://github.com/0abc/0abc-svn#gameplay-balance)
* [Organizatorial changes](https://github.com/0abc/0abc-svn#organizatorial)
* [Committed patches](https://github.com/0abc/0abc-svn#committed)

## Gameplay Balance
Also available, although not included in this mod:
* [D896](https://code.wildfiregames.com/D896): Disabled training cavalry at civil centres.
* [D1762](https://code.wildfiregames.com/D1762): Give fortress a territory root.
* [D1863](https://code.wildfiregames.com/D1863): Reduce Blemmye and Nuba camp building time.
* [D2202](https://code.wildfiregames.com/D2202): Enable archery tradition for kush.
* [D2300](https://code.wildfiregames.com/D2300): Single walking speed for all citizen infantry.
* [D2477](https://code.wildfiregames.com/D2477): Garrison units on short wall segments.

[(return to table of contents)](https://github.com/0abc/0abc-svn#table-of-contents)

## Organizatorial
Also available, although not included in this mod:
* [D888](https://code.wildfiregames.com/D896): Regrouped special technologies.
* [D918](https://code.wildfiregames.com/D918): Technology naming consistency: storehouse and farmstead researches.
* [D1775](https://code.wildfiregames.com/D1775): Delete unused technologies.

[(return to table of contents)](https://github.com/0abc/0abc-svn#table-of-contents)

## Committed
The following patches have been included into Alpha XXIV already:
* [rP22005](https://code.wildfiregames.com/rP22005): Correct Mauryans into Mauryas.
* [rP22014](https://code.wildfiregames.com/rP22014): Fix inconsistencies between specific name and generic name.
* [rP22026](https://code.wildfiregames.com/rP22026): Remove unnecessary gaia from other/ structures.
* [rP22031](https://code.wildfiregames.com/rP22031): Templates for domestic horse and camel.
* [rP22083](https://code.wildfiregames.com/rP22083): Group civ bonuses into a single folder.
* [rP22061](https://code.wildfiregames.com/rP22061): Merge entity templates, removing two templates with non descriptive names.
* [rP22115](https://code.wildfiregames.com/rP22115): Move the fish template under template_gaia since fish is a resource like trees and mines.
* [rP22116](https://code.wildfiregames.com/rP22116): Nuke the misleading Structure_Defence from the wallset template name.
* [rP22118](https://code.wildfiregames.com/rP22118): Remove a misleading unit_fauna_decorative from the bird template.
* [rP22120](https://code.wildfiregames.com/rP22120): Change structure_defense to structure_defensive so it is consistent with the other structure types.
* [rP22163](https://code.wildfiregames.com/rP22163): Remove unneeded death sounds from structure templates, as they inherit from template_structure.
* [rP22181](https://code.wildfiregames.com/rP22181): Reduce duplication in template_structure_military*.
* [rP22182](https://code.wildfiregames.com/rP22182): Add ConquestCritical to structures that want it, instead of removing it from those that don't want it.
* [rP22190](https://code.wildfiregames.com/rP22190): Unparent the range from the barracks, and reduce the duplication in the civs' range templates.
* [rP22202](https://code.wildfiregames.com/rP22202): Bring the palisade templates under their own parent (instead of the stone wall).
* [rP22256](https://code.wildfiregames.com/rP22256): Removes <Actor> from the generic template_* files.
* [rP22315](https://code.wildfiregames.com/rP22315): New horse and cattle fauna template corrections.
* [rP22322](https://code.wildfiregames.com/rP22322): Seperate stable from barracks.
* [rP22325](https://code.wildfiregames.com/rP22325): Reduce defensive_wall* duplication.
* [rP22329](https://code.wildfiregames.com/rP22329): Merge archery tradition.
* [rP22502](https://code.wildfiregames.com/rP22502): Clean Gaia's Selectable.
* [rP22731](https://code.wildfiregames.com/rP22731): Rename gastraphetes template corrects the <Identity> node.
* [rP22787](https://code.wildfiregames.com/rP22787): Move other/wallset_palisade to structures/wallset_palisade.
* [rP22809](https://code.wildfiregames.com/rP22809): Change CitizenSoldier class to Citizen and/or Soldier in auras and technologies.
* [rP22810](https://code.wildfiregames.com/rP22810): Remove Mechanical class in favour or using Siege and Ship.
* [rP22824](https://code.wildfiregames.com/rP22824): Match unit classes with templates names.
* [rP22984](https://code.wildfiregames.com/rP22984): Enable workshops for all civilisations.

[(return to table of contents)](https://github.com/0abc/0abc-svn#table-of-contents)