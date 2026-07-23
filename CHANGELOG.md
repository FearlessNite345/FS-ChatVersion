# Changelog v1.3.0
- Added full FiveM `chat` resource replacement support, improving compatibility with resources that use the default chat API.
- Added support for standard chat messages, suggestions, templates, hooks, and custom chat modes.
- Added the ACE-protected `/chatcommands` editor for creating, styling, previewing, deleting, and publishing custom commands without restarting.
- Added persistent custom-command settings for badge colors, help text, global or proximity routing, radius, and optional ACE permissions.
- Added channel-aware chat modes and refreshed the chat settings and command-editor interfaces with improved focus and close behavior.

# Changelog v1.2.0
- Added new chat command aliases: `/med` and `/gmed`. These commands function as direct alternatives to `/ems` and `/gems`.  
- Added configurable chat anchor points, enabling players to choose where the chat interface appears on their screen.  
- Added a wide range of new chat customization settings, giving players significantly more control over chat appearance, layout, and overall visual behavior.  

# Changelog v1.1.0
- Added new chat commands: `/fire`, `/gfire`, and `/ad` to improve roleplay communication and announcements.  
- Introduced a new quote/reply feature allowing players to directly respond to specific chat messages, helping others nearby see who you’re replying to.  
- Added `Config.SuppressNonCommandMessages` to control whether non-command messages appear in chat. When true, only recognized commands (like `/me`, `/do`, `/leo`, `/gfire`, `/ad`) will be shown.  
- Added `Config.ShowPlayerJoinLeave` to toggle whether player join and leave messages are displayed in chat.
