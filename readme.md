### wowcdns_builds
- This tool removes WoW Cache files before launching WoW (Download: [WoW CacheDeleter & Starter (Universal).exe](https://github.com/Wruktarr/wowcdns_builds/raw/master/~rls/WoW%20CacheDeleter%20%26%20Starter%20(Universal).exe)).
- Notice: You need to put WoW CacheDeleter & Starter (Universal).exe to your WoW folder where WoW.exe or WoW-64.exe is.

#### Optional 'wowcdns.cfg' file usage
- You can create file named 'wowcdns.cfg' inside WoW folder where WoW executable is, you can determine which WoW executable will be launched.
- For example, if CustomWoWExecutable.exe is written in wowcdns.cfg file, WoW CacheDeleter & Starter (Universal).exe will start that defined CustomWoWExecutable.exe instead of launching WoW.exe or WoW-64.exe after Cache files removal.

#### Optional 'WoW.<span>@</span>RunOverride.exe' usage
- Similarly to 'wowcdns.cfg', you can rename your prefered executable to 'WoW.<span>@</span>RunOverride.exe' which will be started instead of WoW.exe or WoW-64.exe (Notice: if 'wowcdns.cfg' exists, file written in it has higher launch priority that 'WoW.<span>@</span>RunOverride.exe' so it will be ignored).
- If you want to determine which executable to start, rather use 'wowcdns.cfg'.
