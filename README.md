# isaac-vscode-template
A very opinionated VSCODE config for the Isaac LUA API
> [!NOTE]
> So obviously it works way better if the whole team is using VSCode

If you use the `filloax.isaac-lua-api-vscode` extension, you probably do not want to commit your `.luarc`,
So instead you can use the vscode `.settings`.

- The `settings.json` file is documentated (JSONC) and can be copy and pasted into your `.vscode` directory.
- The `extensions.json` is just a list of recommended extensions to work on an Isaac project:
  - The Lua LS
  - The Lua API for Isaac
  - The XML LS

### XML schemas
I know that wofsauge already did XML schemas, but these one works with REPENTOGON.
You just need to put them *locally* in some directory of your project (I use `content/xml_schemas`), then bind the real `.xml` file to the `.rng` file inside the `settings.json`.
