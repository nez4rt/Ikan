# 🐟 Konfigurasi Abbr Fish Shell — Semua Distro

Kumpulan abbreviation (abbr) buat Fish Shell yang udah dipisah per distro, biar gampang nyari & copas sesuai OS yang dipake.

> 💡 **Abbr** itu beda sama alias — abbr bakal "expand" jadi command aslinya begitu lo tekan spasi/enter di terminal, jadi history tetep bersih dan gampang di-edit lagi.

---

## 📦 Ubuntu (pakai Nala)

```fish
abbr -a ff "fastfetch"
abbr -a cls "clear"
abbr -a nari "nala search"
abbr -a nasa "sudo nala install"
```

| Abbr | Command Asli | Fungsi |
|------|-------------|--------|
| `ff` | `fastfetch` | Nampilin info sistem |
| `cls` | `clear` | Bersihin terminal |
| `nari` | `nala search` | Cari paket |
| `nasa` | `sudo nala install` | Install paket |

---

## 📦 Fedora (pakai DNF)

```fish
abbr -a ff "fastfetch"
abbr -a cls "clear"
abbr -a nari "dnf se"
abbr -a nasa "sudo dnf install"
```

| Abbr | Command Asli | Fungsi |
|------|-------------|--------|
| `ff` | `fastfetch` | Nampilin info sistem |
| `cls` | `clear` | Bersihin terminal |
| `nari` | `dnf se` | Cari paket |
| `nasa` | `sudo dnf install` | Install paket |

---

## 📦 Arch Linux (pakai Pacman & Paru)

```fish
abbr -a ff "fastfetch"
abbr -a cls "clear"
abbr -a pari "pacman -Ss"
abbr -a pasang "sudo pacman -S"
abbr -a yari "paru -Ss"
abbr -a yasa "paru -S"
abbr -a upd "sudo pacman -Syu"
abbr -a del "sudo pacman -Rns"
```

| Abbr | Command Asli | Fungsi |
|------|-------------|--------|
| `ff` | `fastfetch` | Nampilin info sistem |
| `cls` | `clear` | Bersihin terminal |
| `pari` | `pacman -Ss` | Cari paket (official repo) |
| `pasang` | `sudo pacman -S` | Install paket (official repo) |
| `yari` | `paru -Ss` | Cari paket (AUR) |
| `yasa` | `paru -S` | Install paket (AUR) |

---

## 🚀 Cara Pakai

1. Buka file config fish, biasanya di `~/.config/fish/config.fish`
2. Copas bagian yang sesuai sama distro lo
3. Save & reload dengan:
   ```fish
   source ~/.config/fish/config.fish
   ```
4. Coba ketik `ff` lalu spasi/enter — bakal auto-expand jadi `fastfetch` ✨

---

## 📝 Catatan

- `ff` dan `cls` sama di semua distro, jadi kalau lo dual-boot atau pindah-pindah OS, dua abbr ini gak perlu diinget ulang.
- Naming abbr pakai gaya Bahasa Indonesia (`nari` = cari, `nasa` = pasang, `pasang`, `yasa`) biar lebih nyantol di kepala.
