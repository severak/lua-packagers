# lua package managers comparasion

## LuaRocks

* living at [luarocks.org](https://luarocks.org/)
* oldest lua package manager
* needs change the `package.path`? [no](https://github.com/luarocks/luarocks/wiki/File-locations#paths-to-rocks-trees)
* can distribute binaries? [yes](https://github.com/luarocks/luarocks/wiki/Rock-file-format)
* needs compiler? Usually, there are not many modules with binaries provided.
* package description syntax: [rockspec](https://github.com/luarocks/luarocks/wiki/Rockspec-format) (lua-based)
* packages hosted at: custom website ([luarocks.org](https://luarocks.org/))

## LuaDist

* living at [luadist.org](http://luadist.org/)
* based on CMake, Git
* needs change the `package.path`? N/A
* can distribute binaries? [yes](https://github.com/LuaDist/Repository/wiki/LuaDist%3A-Package-Structure)
* needs compiler? Sometimes, for common platforms there are binaries provided usually.
* package description syntax: [dist.info](https://github.com/LuaDist/Repository/wiki/LuaDist:-Package-Structure#the-distinfo-file) (lua-based)
* packages hosted at: [github repository](https://github.com/LuaDist/Repository)

## LuaDist2

* new version of LuaDist, currently in development
* living at [github.com/LuaDist2](https://github.com/LuaDist2)
* needs change the `package.path`? N/A
* can distribute binaries? probably not
* needs compiler? Yes
* package description syntax: LuaRock's [rockspec](https://github.com/luarocks/luarocks/wiki/Rockspec-format) (lua-based)
* packages hosted at: [github repository](https://github.com/LuaDist2/manifest)

---

* ULua (http://ulua.io/)
* luapower (https://luapower.com/)
* Open resty package manager (https://opm.openresty.org/)
* [LIT](https://github.com/luvit/lit) - Luvit Invention Toolkit
* ActiveLua own's (any info available?)

## Comparasion criterias

* based on *what*?
* changes to `package.path`?
* can into binary modules?
* needs compiler?
* package description syntax
* packages (can be) hosted at *what*?
* luarocks compatibilty?
* is it one man show?

## Build systems

* [heroku buildpack](http://leafo.net/posts/lua_on_heroku.html)
* luawinmulti (https://github.com/Tieske/luawinmulti)
* luastatic (https://github.com/ers35/luastatic)
* Omnia (https://github.com/tongson/omnia)
* luabuild (https://github.com/stevedonovan/luabuild)


## Distros

*(provided only for examples, not going to examine these)*

* Lua for Windows (https://github.com/rjpcomputing/luaforwindows)
* LuaAIO (http://luaaio.luaforge.net/index.html)
* MurgaLua (http://www.murga-projects.com/murgaLua.html)
* LuaPlus (http://luaplus.org/)
* etc etc
