### wowcdns_builds

#### Optional 'wowcdns.cfg' file usage
- You can create file named 'wowcdns.cfg' inside WoW folder where WoW executable is, you can determine which WoW executable will be launched.
- For example, if CustomWoWExecutable.exe is written in wowcdns.cfg file, WoW CacheDeleter & Starter (Universal).exe will start that defined CustomWoWExecutable.exe instead of launching WoW.exe or WoW-x64.exe after Cache files removal.

#### Optional 'WoW.<span>@</span>RunOverride.exe' usage
- Similarly to 'wowcdns.cfg', you can rename your prefered executable to 'WoW.<span>@</span>RunOverride.exe' which will be started instead of WoW.exe or WoW-x64.exe (Notice: if 'wowcdns.cfg' exists, file written in it has higher launch priority that 'WoW.<span>@</span>RunOverride.exe' so it will be ignored).
- If you want to determine which executable to start, rather use 'wowcdns.cfg'.
