# ScriptHookV
- ScriptHookV is a standalone script hook for Grand Theft Auto V.

## Features
- Custom *.asi loader which is compatible with existing GTA:V mods
- Ability to create standalone mods/scripts
- in addition to the imports in the original ScriptHook by Alexander Blade
  we can 'changeScriptThread' | registerRawStreamingFile

## Usage
- *.asi scripts will load from an /asi directory directly from where you inject this dll,
or alternatively directly from the GTAV directory itself.
- You can unload all loaded *.asi using PageUp_key, Reload them all using PageDown_key.
- For Developers of ScriptHook itself you can unload the whole hook using End_key.

## Credits
- [NTAuthority/citizenMP](http://tohjo.eu/citidev/citizenmp) Some inspiration taken from these guys but entirely rewritten.
- [Alexander Blade](http://www.dev-c.com/) For his ScriptHookV SDK files which can also be used with our ScriptHookV.
- [Brick] For his Memory Class / joaat function and advice.
