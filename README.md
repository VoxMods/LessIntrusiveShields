##Shield Rework
-------------------------

SR reworks the shields added in vanilla Minecraft 1.9. This adds cosmetic changes as well as changing the transformations of the shields to fill less screen space, so more of the screen is uncovered for PvP and building.

#####Features:
 - Shields now take up less screen space in first person (both hands) and have changed transforms for third person.
  - Though some of these visual effects could be modified by a resource pack, that would also change the position of the shield during blocking.
  - Configurable to lower when holding a block, or to lower always.

#####Planned:
 - Make shields retain coloring when repaired
 - Shield enchanting (Unbreaking, Mending, custom enchantments)
 - Enable "washing" in cauldron, similar to vanilla banners
 - Let the coloring of the shield be replaced with a new banner
 - Remove consumption of banner during coloring (configurable)

#####Changelog:
  - v1.1:
   - Add configuration option for shield behavior
    - Always lowered (or)
    - Lowered when holding block
  - v1.2:
   - Add configuration option to shield behavior
    - Completely hidden, I.e. does not show up on screen at all.

#####Configuration:
 - general:
  - shieldBehavior
   - Set to 0 (or any other unused number, since this is default) to set shield to lower only when holding a block
       - Warning, setting this to a number other than 0 may lead to unintended behavior in updated versions of this mod if that number becomes used.
   - Set to 1 to set shield to always lower
   - Set to 2 to set shield to always be hidden (I.e. does not show up on screen)

Created by [Vox](http://github.com/WardBenjamin).

Inspired by DireWolf20 and the ForgeCraft2 crew.

Logo by [Biochemic](https://github.com/TheBiochemic)

Pull Requests
---------------

Pull requests with new features, translations, and bugfixes are very welcome. Please make sure to always submit PRs against the ***dev*** branch, not master.

Do not make PRs that are solely formatting or other aesthetic things.

If your PR is going to take a lot of work, it may be best to make an issue so we can discuss the feature before you create it.

Issue Reporting
----------------
If you wish to report an issue with the mod, please submit one to the issue tracker in this repository.  When creating an
issue, please be sure to include:

- The version of SR you are using ("latest" is not an acceptable version)
- The version of Forge you are using
- If applicable, the crash report (preferably via [Pastebin](http://pastebin.com/)). generated by the error
- Depending on the error, an image of the problem
