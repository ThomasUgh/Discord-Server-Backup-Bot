# 🔄 Discord Server Backup Bot
Ein einfacher Discord Bot zum Sichern und Wiederherstellen von Discord Server-Strukturen.

## ✨ Features

- **`/backupserver`** - Erstellt ein vollständiges Server-Backup (JSON-Format)
- **`/backupload`** - Stellt ein Backup auf dem aktuellen Server wieder her
- **`/transferserver`** - Überträgt Server-Struktur direkt zu einem anderen Server
- **`/backuphelp`** - Zeigt Hilfe-Informationen

### Was wird gesichert?
- ✅ Rollen (inkl. Berechtigungen, Farben, Positionen)
- ✅ Kategorien
- ✅ Text-Channels (inkl. Topic, Slowmode, NSFW)
- ✅ Voice-Channels (inkl. Bitrate, User-Limit)
- ✅ Forum-Channels
- ✅ Stage-Channels
- ✅ Channel-Berechtigungen (Overwrites)
- ✅ Emoji-URLs

### Was wird NICHT gesichert?
- ❌ Nachrichten
- ❌ Mitglieder
- ❌ Bans
- ❌ Webhook-Konfigurationen

## 📄 Lizenz

MIT License - siehe [LICENSE](LICENSE)

---
Erstellt von [ThomasUgh](https://github.com/ThomasUgh)
