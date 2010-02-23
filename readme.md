Open RPG Maker
==============


About
-----

**Open RPG Maker** is a clone of [RPG Maker XP][1]. The goal is to create a cross platform re-implementation of the RMXP library, written in 100% Ruby. All GUI related code is modular so as to support platform-specific forks.

Supported Platforms
-------------------

Linux, OSX and Windows are all supported. These are the following primary GUI platforms we are targeting:

 - FXRuby
 - Silverlight/IronRuby

Status
------

A majority of the core library is implemented, leaving the intricacies of the GUI code for last. As they say, the last 10% of functionality represents 90% of the development time.

Roadmap
-------

There's still a *lot* to do right now:

 1. Recreate the resource files (*.rxdata) in an unencrypted format.
 2. Finish the *RPG* module, and create the *load_data(filename)* and *save_data(obj, filename)* bult-ins.
 3. Redefine *p* and *print* for use in message box output.
 4. Document the *RPG* module.
 5. Create the bootstrapper for WPF, Silverlight, and WinForms.
 6. Create unit tests.
 7. Figure out what this is (from troop.rb): RPG::BattleEventPage.new


  [1]: http://tkool.jp/products/rpgxp/eng
