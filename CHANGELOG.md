# Changelog

Player-friendly release notes for WhisperMessenger. This file covers the current 2.x series; older series live in [archive/changelog/](archive/changelog/).

All releases: **2.2.x (current)** · [2.1.x](archive/changelog/2.1.md) · [2.0.x](archive/changelog/2.0.md) · [1.4.x](archive/changelog/1.4.md) · [1.3.x](archive/changelog/1.3.md) · [1.2.x](archive/changelog/1.2.md) · [1.1.x](archive/changelog/1.1.md) · [1.0.x](archive/changelog/1.0.md) · [0.1.x](archive/changelog/0.1.md)

## [Unreleased]

- Fixed: Copy Character Name in the right-click menu of a chat or a message no longer shows an error. It opens a small box with the name selected, ready to copy with Ctrl+C. In WoW: Forever it copies the name without the realm, like the game's own menu does.
- Fixed: In WoW: Forever, a Battle.net friend's character name at the top of the chat no longer ends in a long server code.
- Right-clicking a player in the contact list now offers "Guild invite" when you're allowed to invite: it types the invite command into your chat box, and you press Enter to send it. It's hidden for your guildmates, and (with "Show player levels" on) for players the game has shown you in another guild this session.

## [2.2.3] - 2026-11-05

- Fixed: on the Off and Classic window styles, the messenger button now settles into the window's top-left corner when it opens, the same way it does on the Retail style.
- Fixed: Reset to Defaults no longer asks you to reload the interface when your window style didn't change.
- Fixed: the phone-style window now grows smoothly out of the messenger button, and shrinks back into it when you close it.
- New phone-style window, on by default: the messenger button grows into the window's top-left icon and opens a tall, phone-sized list of your chats. Click a chat to slide into it, and use the back arrow to slide back. The button keeps your unread count the whole time, and dragging the window takes the button with it.
- Closing the phone-style window sends the icon back to where it came from. Settings open wider while they're showing, then the window returns to phone size. You can switch back to the classic window under Appearance settings.
- New option in Behavior settings, off by default: Deselect chat input after sending. After you send a message, the cursor leaves the text box so your keys control the game again, and Enter puts it back while the messenger is open.
- Smaller download, and the addon now uses less memory by keeping only your language loaded.
- Changing to a language that isn't loaded now asks you to reload the interface.
- The messenger button and the minimap button now share one look on every theme: a dark circle with the two chat bubbles on it, framed by a ring. The minimap button's ring is always gold; the messenger button's ring takes your theme's color, or gold if you prefer. Hovering lifts the circle a little so the bubbles stay easy to see on any theme, and the minimap button now reacts to the mouse as well.
- When there are no unread messages, only the back chat bubble turns gray, and it is brighter than before so it stands out on the dark circle. The front bubble and the circle keep their colors.
- The sender's name on the message preview next to the button is smaller, so it fits the small card better.
- New Icons setting, Widget shape: pick a round or a square messenger button on any theme, and it changes right away without a reload.
- New options in Icons settings for the messenger button: Show border and Color border with theme (the minimap button always keeps its gold ring), and Button background now works on the round widget too.
- EllesmereUI theme: the messenger button is now round like on the other themes. To get the square back, open Settings, go to Icons, and set Widget shape to Square.
- The addon's own icon, shown in the addon list, the minimap addon menu, the empty chat picture and the window portrait, now matches the new button look.
