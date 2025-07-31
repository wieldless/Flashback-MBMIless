<h1 align="center">Flashback - MBMIless</h1>

Copyright 2024 Moulberry. Do not reupload or redistribute.

**This is a fork of the original Flashback mod.** - [Discord](https://discord.gg/flashbacktool)

Flashback is a Minecraft mod which allows you to record your Minecraft gameplay, play it back and create stunning cinematic shots.

This fork excluded MixinBiomeModificationImpl to make this mod work with Sinytra Connector again since 0.13.0 (commit [67aa3c1](https://github.com/Moulberry/Flashback/commit/67aa3c1401588a24fed0e5c174992b6f81190778)), but since commit [f67e817](https://github.com/Moulberry/Flashback/commit/f67e817b71a2ab18e04370a7ea734f8192d48cdb#diff-ef2fd02b0039815cf08d21b86d0b2a7e2d817a2f0a7676b451203f45377e0dda) from upstream, MixinBiomeModificationImpl will simply be ignored under Sinytra, solving [this issue](https://github.com/Sinytra/Connector/issues/1678).

This fork contains a hotfix to make players visible with e.g. Create, the issue is discussed here:
https://github.com/Sinytra/Connector/issues/1452 - Please refer to https://github.com/Qubik65536/Flashback-InvisiblePlayerFix/tree/1.21 for further development on that

## How to install
1. Install NeoForge (https://neoforged.net/)
2. Dowload Sinytra Connector (https://modrinth.com/mod/connector) & Forgified Fabric API (https://modrinth.com/mod/forgified-fabric-api)
3. Put each mod's JAR into your mods folder (.minecraft/mods)
4. Run the game

## Support

As this is not an intended way to run Flashback so **expect no support, I'm also not a coder and this solution just happened to work for me.**

## Contributing

Flashback currently does not accept outside contributions

## License

This project is licensed with a custom license, see [LICENSE.md](https://github.com/Moulberry/Flashback/blob/master/LICENSE.md)
