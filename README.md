# clawed

`clawed` helps provide project contexts to `Claude`

## Affordances

`clawed` can, for each project, e.g.
- keep histories of chats with Claude
- enforce a Pythonic "style"
- transcibe meetings and extract "TODOs" from them

## Architecture

`clawed` provides an MCP server that `Claude` can call

`clawed` maintains a directory per project
`clawed`'s project directories are kept separate from the projects themselves
  - but can be linked in there as needed (e.g. the MCP [Serena](https://github.com/oraios/serena) needs that)


