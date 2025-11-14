# 🔐 Tenny-Carlock

🇹🇷 [Türkçe](#turkish) | 🇬🇧 [English](#english)

---

## 🇹🇷 Turkish

### ESX, QBCore ve QBX uyumlu araç kilitleme scripti.

#### 🎯 Özellikler

- ✅ ESX, QBCore ve QBX otomatik algılama
- 🔑 L tuşu ile araç kilitleme/açma
- 🚗 Yakındaki araçları kilitleme desteği
- 🛡️ Sadece sahip olunan araçları kilitleme
- 🚫 Kilitli araçtan inmeyi engelleme
- 🎬 Kilit animasyonu
- 🔊 Araç kilit sesleri
- ⏱️ Spam engelleme sistemi
- 🌍 Türkçe ve İngilizce dil desteği

#### 📥 Kurulum

1. `tenny-carlock` klasörünü sunucunuzun `resources` dizinine atın
2. `server.cfg` dosyanıza `ensure tenny-carlock` ekleyin
3. `oxmysql` ve `tenny-notify` scriptlerini yükleyin (bağımlılık)
4. Sunucuyu yeniden başlatın

#### ⚙️ Yapılandırma

`shared/config.lua` dosyasından tüm ayarları özelleştirebilirsiniz:
- Framework seçimi (ESX/QBCore/QBX - Otomatik)
- Kilit tuşu (Varsayılan: L)
- Araç arama mesafesi
- Spam engelleme süreleri
- Bildirim ayarları
- Animasyon ayarları

#### 🎮 Kullanım

- **L tuşu**: Araç içindeyken veya yakınındayken kilitle/aç
- Sadece sahip olduğunuz araçları kilitleyebilirsiniz
- Kilitli araçtan inemezsiniz (önce kilidi açın)

#### 📜 Lisans

Bu script, **Tenny** tarafından oluşturulmuştur.

Bu lisans altında:
- ✅ Script ücretsiz olarak kullanılabilir
- ❌ Script ticari amaçla kullanılamaz veya satılamaz
- ❌ Script değiştirilemez veya türevleri oluşturulamaz
- ⚠️ Paylaşılması durumunda Tenny'nin adı belirtilmelidir

---

## 🇬🇧 English

### ESX, QBCore and QBX compatible vehicle lock script.

#### 🎯 Features

- ✅ ESX, QBCore and QBX auto-detection
- 🔑 Lock/unlock vehicles with L key
- 🚗 Lock nearby vehicles support
- 🛡️ Lock only owned vehicles
- 🚫 Prevent exiting locked vehicles
- 🎬 Lock animation
- 🔊 Vehicle lock sounds
- ⏱️ Spam prevention system
- 🌍 Turkish and English language support

#### 📥 Installation

1. Place the `tenny-carlock` folder in your server's `resources` directory
2. Add `ensure tenny-carlock` to your `server.cfg` file
3. Install `oxmysql` and `tenny-notify` scripts (dependencies)
4. Restart your server

#### ⚙️ Configuration

You can customize all settings from the `shared/config.lua` file:
- Framework selection (ESX/QBCore/QBX - Auto)
- Lock key (Default: L)
- Vehicle search distance
- Spam prevention delays
- Notification settings
- Animation settings

#### 🎮 Usage

- **L key**: Lock/unlock when inside or near a vehicle
- You can only lock vehicles you own
- You cannot exit locked vehicles (unlock first)

#### 📜 License

This script was created by **Tenny**.

Under this license:
- ✅ Script can be used for free
- ❌ Script cannot be used commercially or sold
- ❌ Script cannot be modified or derivatives created
- ⚠️ If shared, Tenny's name must be credited

---

## 👤 Developer / Geliştirici

**Tenny**

## 💬 Discord

[![Discord](https://img.shields.io/discord/YOUR_SERVER_ID?color=7289da&label=Discord&logo=discord&logoColor=white)](https://discord.gg/ZBuNKA6ZxQ)

Destek ve güncellemeler için Discord sunucumuza katılın!

Join our Discord server for support and updates!
