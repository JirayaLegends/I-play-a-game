# I-play-a-game
static void UpdatePresence() {     DiscordRichPresence discordPresence;     memset(&amp;discordPresence, 0, sizeof(discordPresence));     discordPresence.state = "Playing Solo";     discordPresence.details = "Competitive";     discordPresence.startTimestamp = 1507665886;     discordPresence.endTimestamp = 1507665886;     discordPresence.largeImageKey = "my_naruto_gg";     discordPresence.largeImageText = "Snow Comunity";     discordPresence.smallImageKey = "gggggg";     discordPresence.smallImageText = "Rogue - Level 100";     discordPresence.partyId = "ae488379-351d-4a4f-ad32-2b9b01c91657";     discordPresence.partySize = 1;     discordPresence.partyMax = 5;     discordPresence.joinSecret = "MTI4NzM0OjFpMmhuZToxMjMxMjM= ";     Discord_UpdatePresence(&amp;discordPresence); }
