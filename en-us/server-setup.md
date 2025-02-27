# Server setup

Fabulously Optimized is a strictly client-sided modpack, meaning it works and behaves the same on every server that allows vanilla clients. 

**Yes, the CurseForge listing has a section of "server packs", but those are actually just the MultiMC versions that are marked as server packs for better visibility.**

For server software I recommend using [Paper](https://papermc.io), which is a performance-optimized fork of Spigot, but supports all the same plugins. Definitely install the mod [No Encryption](https://www.spigotmc.org/resources/noencryption.102902/) (the name is a bit misleading, should rather be "No Chat Signing") to protect your players from some account-wide bans.

If you still like Fabric a lot, you can also [use that on a server too](https://fabricmc.net/use/?page=server) and check out [comp500's list](https://github.com/comp500/fabric-serverside-mods#performance) for some great server-side mods. I highly recommend the mod [No Chat Reports](https://www.curseforge.com/minecraft/mc-mods/no-chat-reports) as well to protect your server players. There is a mod called Cardboard that lets you use Fabric with Spigot, [but is not recommended](https://gist.github.com/Patbox/e44844294c358b614d347d369b0fc3bf) - just pick one or the other.

On vanilla servers, just make sure `enforce-secure-profile` is set to `false` (should be by default though).

If you need a host, [check out BisectHosting](https://www.bisecthosting.com/clients/aff.php?aff=2604). This affiliate link will give you 25% off for the first month.
