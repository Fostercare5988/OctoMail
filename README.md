# OctoMail

A mailbox enhancement for WoW 1.12, made for [OctoWoW](https://octowow.st).
Maintained by **Fostercare5988**.

This is a fork of **[TurtleMail](https://github.com/sica42/TurtleMail)** by **shirsig** and
**sica42**. Nearly all of the work is theirs.

## Requirements

- WoW 1.12.1 client (the OctoWoW client)
- [ClassicAPI](https://github.com/brues-code/ClassicAPI) 1.17.7 or newer. OctoMail does not load without it.

## What it does

- **Open All** takes the money and items from every mail in one click. C.O.D. and GM mail are skipped.
  Right-click a mail to take its contents.
- **Send up to 21 attachments** at once. Each item goes out as its own mail with a numbered
  subject. Right-click a bag item while the mailbox is open to attach it.
- **C.O.D. for every mail**: tick *All mails* to charge the C.O.D. on each mail, not only the first.
- **Recipient autocomplete** from people you have mailed or received mail from, your friends and
  your guild. Press Tab to cycle. Names unused for 30 days are dropped.
- **Mail log** (off by default): a searchable record of mail sent and received, with filters
  for money, C.O.D., returned and auction mail, by player and by date. Turn it on with `/om log`.
- Auction House and returned mail are marked in the inbox.

Sending gold asks for confirmation, as in the default mailbox.

## Commands

`/om` or `/octomail`:

| Command | Effect |
| --- | --- |
| `/om log` | Turn the mail log on or off |
| `/om clear sent` | Clear the sent log |
| `/om clear received` | Clear the received log |
| `/om clear names` | Forget saved autocomplete names |

## Install

1. [Download](https://github.com/Fostercare5988/OctoMail/archive/refs/heads/main.zip) and unpack the zip.
2. Rename the folder `OctoMail-main` to `OctoMail`. WoW only loads an addon whose folder name
   matches its `.toc` file.
3. Move `OctoMail` into `Interface\AddOns` and restart WoW.

## Credits

- **[shirsig](https://github.com/shirsig)** and **[sica42](https://github.com/sica42/TurtleMail)**
  wrote TurtleMail, which is most of this addon.
- **Roby_Brok** made the OctoMail fork: the rename, and fixes for autocomplete expiry and an
  unbounded mail log.
