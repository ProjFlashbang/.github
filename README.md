<h1 align="center">Project Flashbang</h1>
<p align="left">Project Flashbang is private remake of services like CS Supremacy made for me and friends,</p>
<p>project will slowly start to be open source excluding some parts because the project grew bigger than i planned and i would feel weird gatekeeping this</p>


<h2>Main repositories</h2>
<ul>
  <li>Outpost - Game Coordinator used by this project.</li>
  <li>Breakout - Library for parsing cases and items from items_game.txt and csgo_english.txt</li>
  <li>Scout - Client for game coordinator</li>
  <li>Hydra - Game Server plugin handling almost everything</li>
  <li>Seaside - Discord bot for this project</li>
  <li>FakeProfile - Game Server plugin making bots look like real players</li>
  <li>Phoenix - Launcher used in early stage of project</li>
</ul>

<h2>Technical details</h2>
<ul>
  <li>Outpost - written in C# since late 2025, already has many features such as: Match drops, Match logic, XP system, Overwatch, Ranking system, Case opening, Trading system, Match API, Discord bot API etc. Uses websocket to communicate instead of classic tcp sockets.</li>
  <li>Breakout - written in C# since Jan 2026, Parser for csgo's items & cases exposing parsed entities via classes</li>
  <li>Scout - written in C++ since late 2025, v1 was written from scratch and was known for its very terrible stability, replaced by v2 based on csgo_gc written in Mar 2026</li>
  <li>Hydra - written in SourcePawn since late 2025, Its terrible but works, Has implemented: medals, music kits, music kits ST, skins, knifes, gloves, ranks, auto gotv record by assigned filename on match begin and match system</li>
  <li>Seaside - written in C# since Jan 2026, discord bot having commands such as Key System(used mostly for distributing giveaway items), Inventory, Profile, Daily Music Kit(only way to get music kits), Trading system and many more.</li>
  <li>FakeProfile - written in SourcePawn since Late Jan 2026, Gives bots fake steam ids, random medals, random music kits, random name(TO BE DONE) and random level</li>
  <li>Phoenix - written in C#, HTML, JS And CSS since start of 2026, Does basic job of launching the game and injecting the client, also has key system. This launcher was abandoned after Scout v2 was released as it was no longer needed</li>
</ul>

<h2>Estimated time for exact repository to become public</h2>
<ul>
  <li>Outpost - Unknown, its already in very good state but i don't know if releasing it is good idea</li>
  <li>Breakout - May-June 2026, Its done but currently only parses from json files, and i need to implement converter from key values to json</li>
  <li>Scout - Same time as Outpost</li>
  <li>Hydra - Same time as Outpost, still has many things to be fixed, and probably will be rewritten before release to public</li>
  <li>Seaside - Unknown</li>
  <li>FakeProfile - Most likely never</li>
  <li>Phoenix - Never</li>
</ul>

<h2>Screenshots: </h2>
<p>maybe in future</p>
