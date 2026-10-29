<p align="center">
  <img src="docs/icon.png" width="128" alt="net-merge icon">
</p>

<h1 align="center">net-birlestir</h1>

<p align="center">
  <strong>Windows, macOS, Linux ve Android işletim sistemlerinde tüm internet bağlantılarınızı aynı anda kullanın.</strong><br>
  Wi‑Fi, Ethernet, mobil veri ve telefon internet paylaşımı üzerinden bağlantı başına yük dengeleme.
</p>

<p align="center">
  <a href="#türkçe-kısa-özet">Türkçe özeti</a> ·
  <a href="#kurulum">Kurulum</a> ·
  <a href="#android">Android</a> ·
  <a href="#sorun-giderme">Sorun giderme</a> ·
  <a href="#english">English</a>
</p>

<p align="center">
  <a href="https://net-merge.org">Website</a> ·
  <a href="https://github.com/net-merge/net-merge/releases/latest">İndir</a> ·
  <a href="#android">Android</a> ·
  <a href="#kurulum">Kurulum</a> ·
  <a href="#ikinci-baglanti-ekleme">İkinci bağlantı ekle</a> ·
  <a href="#sorun-giderme">Sorun giderme</a> ·
  <a href="docs/DEVELOPING.md">Nasıl çalışır</a>
</p>

<p align="center">
  <a href="https://github.com/net-merge/net-merge/actions/workflows/ci.yml"><img src="https://github.com/net-merge/net-merge/actions/workflows/ci.yml/badge.svg" alt="CI"></a>
  <a href="https://github.com/net-merge/net-merge/releases"><img src="https://img.shields.io/github/v/release/net-merge/net-merge" alt="Son sürüm"></a>
  <a href="https://github.com/net-merge/net-merge/releases"><img src="https://img.shields.io/github/downloads/net-merge/net-merge/total" alt="İndirmeler"></a>
  <a href="LICENSE"><img src="https://img.shields.io/github/license/net-merge/net-merge" alt="MIT lisansı"></a>
  <img src="https://img.shields.io/badge/platforms-Windows%20%7C%20macOS%20%7C%20Linux%20%7C%20Android-blue" alt="Windows, macOS, Linux ve Android">
  <a href="https://buymeacoffee.com/rohit267"><img src="https://img.shields.io/badge/Buy%20me%20a%20coffee-rohit267-FFDD00?logo=buymeacoffee&logoColor=black" alt="Bana kahve ısmarla"></a>
  <a href="https://paypal.me/champdev"><img src="https://img.shields.io/badge/Donate-PayPal-00457C?logo=paypal&logoColor=white" alt="PayPal ile bağış yap"></a>
</p>

<p align="center">
  <a href="https://trendshift.io/repositories/301802?utm_source=trendshift-badge&amp;utm_medium=badge&amp;utm_campaign=badge-trendshift-301802" target="_blank" rel="noopener noreferrer"><img src="https://trendshift.io/api/badge/repositories/301802" alt="Trendshift" /></a>
  <a href="https://trendshift.io/repositories/301802?utm_source=trendshift-badge&amp;utm_medium=badge&amp;utm_campaign=badge-trendshift-301802" target="_blank" rel="noopener noreferrer"><img src="https://trendshift.io/api/badge/repositories/301802" alt="Trendshift" /></a>
</p>

<p align="center">
  <sub>Aynı geliştiriciden: <a href="https://dormhost.dev/?utm_source=net-merge&utm_medium=readme"><strong>DormHost</strong></a>, üniversite projenizi
  çevrimiçi yayınlayın. Node.js, Python veya Docker ile veritabanı, 30 gün ücretsiz.</sub>
</p>

<p align="center">
  <strong>Daha fazla kontrol mü istiyorsunuz? <a href="https://github.com/champdev-me/routengine">RoutEngine</a>, net-merge'in geliştirilmiş ticari sürümünü deneyin.</strong><br>
  Her uygulama için bağlantıyı seçin, yedek ekleyin ve uygulama başına hız limiti veya veri kotası belirleyin. Windows, macOS ve Linux. Kişisel kullanım ücretsiz, iş için Pro.
</p>

<p align="center">
  <img src="docs/demo.gif" width="600" alt="Mac'te Wi‑Fi ve Android telefon ile hız testi: net-merge menüsü her iki bağlantının da etkin olduğunu gösteriyor ve indirme yaklaşık 326 Mbit/s ulaşıyor.">
  <br>
  <sub>Bir Mac ile Wi‑Fi + Android telefon. Menü iki bağlantının aynı anda çalıştığını gösteriyor. <a href="docs/demo.mp4">Tam 45 saniyelik videoyu izleyin.</a></sub>
</p>

## Türkçe kısa özet

net-birlestir, birden fazla ağ bağlantısını aynı anda kullanarak toplam bant genişliğini artırır. Wi‑Fi, Ethernet, mobil veri ve telefon paylaşımı gibi farklı bağlantıları birleştirerek daha yüksek toplam veri aktarım hızı elde etmenizi sağlar.

- Wi‑Fi, Ethernet, mobil veri ve telefon paylaşımı gibi birden fazla bağlantıyı aynı anda kullanır.
- Çoklu bağlantı kullanan uygulamalarda hız kazanırsınız.
- VPN, hesap oluşturma veya sunucu gerektirmez.
- Windows, macOS, Linux ve Android için kullanılabilir.
- Daha hızlı bağlantılar otomatik olarak daha fazla trafik alır.
- Çalışmayan bağlantılar otomatik olarak devre dışı kalır.

Aşağıdaki bölümde orijinal İngilizce metin korunmuş şekilde yer almaktadır; Türkçe açıklama bu sayfanın varsayılan görünümüdür.

---

net-merge uses all your network adapters together. It works on **Windows, macOS and Linux**. It is free.
There is no account, no server and no VPN.

A real test with Wi‑Fi + an Android USB tether + an iPhone hotspot, 9 downloads at once:
**232-303 Mbit/s**. The fastest connection alone gave about 121 Mbit/s.

| Windows: hover the icon | Windows: the menu | macOS: the menu bar |
|---|---|---|
| ![Tooltip: Merging, speed of each adapter and the total](docs/tray-tooltip.png) | ![Menu: total, each adapter's speed and flows, IPv6 option, Pause merging, Quit](docs/tray-menu.png) | ![macOS menu bar: green merging icon, app name](docs/macos-menubar.png) |

## Nasıl yardımcı olur

net-merge, yeni her bağlantıyı ağ hatlarınızdan birine dağıtır. Uygulama birden çok bağlantı açtığında,
bunlar tüm bağlantılar arasında paylaşılır.

- **İçin iyi olur:** Steam ve oyun indirmeleri, tarayıcılar, sistem güncellemeleri, bulut yüklemeleri (Google Drive),
  IDM gibi indirme yöneticileri, torrentler.
- **İçin uygun değildir:** tek bir bağlantı. Tek bir bağlantı her zaman tek bir bağlantıyı kullanır; bu yüzden tek bir büyük dosya tek
  bağlantı üzerinden daha hızlı olmaz. Tarayıcılar bir indirmeyi birkaç bağlantıya bölerek hızlandırabilir; bunu [Kullanım](#kullanım) bölümündeki ipucuna bakın.
- **Her uygulama için çalışır**, TCP ve UDP, IPv4 ve IPv6. Proxy kurmazsınız.
- **Akıllı çalışır:** daha hızlı bağlantılar daha fazla bağlantı alır. İnternet erişimi olmayan bir bağlantı tekrar çalışana kadar hiç bağlantı almaz.
- **Güvenli:** net-merge çökerse, internet bağlantınız çalışmaya devam eder.
- **Hafif:** 100 Mbit/s için yaklaşık 0,18 CPU çekirdeği.

## Kurulum

**macOS ve Linux**: bunu terminale yapıştırın.

```sh
curl -fsSL https://raw.githubusercontent.com/net-merge/net-merge/main/install.sh | sh
```

**Windows**: PowerShell'e bunu yapıştırın.

```powershell
irm https://raw.githubusercontent.com/net-merge/net-merge/main/install.ps1 | iex
```

Antivirüs bunu engellediyse? [net-merge-setup.exe](https://github.com/net-merge/net-merge/releases/latest/download/net-merge-setup.exe)
indirin ve çift tıklayarak çalıştırın.

Bu kadar: net-merge kurulur ve menü çubuğunda veya sistem tepsisinde simgesi görünür. Linux'ta kurulum betiği
paket yöneticinizi kullanır (apt, dnf, zypper, apk veya pacman) ve macOS'ta varsa Homebrew kullanır; böylece
net-merge sisteminizle birlikte güncellenir. Oturum açılışta başlatmak için menüsünde *Start at sign-in* (Oturum açılışta başlat) seçeneğini işaretleyin.

**Android**: aşağıdaki [Android](#android) bölümüne bakın.

> **Bağlantıyı her uygulama için seçmek ister misiniz?** [RoutEngine](https://github.com/champdev-me/routengine), net-merge'in
> geliştirilmiş ticari sürümüdür; Windows, macOS ve Linux için. Her uygulama için bir bağlayıcı seçin, yedek ekleyin ve
> uygulama başına hız limiti veya veri kotası belirleyin. Kişisel kullanım ücretsiz, iş için Pro.

<details>
<summary><strong>Kendiniz yazmak istemez misiniz?</strong> Her sistem için tek blok; her biri yapıştırılmaya hazır.</summary>
<br>

**Homebrew** (macOS):

```sh
brew install net-merge/tap/net-merge && sudo "$(brew --prefix)/bin/net-merge" install && net-merge tray
```

**Homebrew olmadan macOS**:

```sh
curl -fsSL https://github.com/net-merge/net-merge/releases/latest/download/net-merge-macos-universal.tar.gz | tar -xz -C /tmp net-merge && sudo /tmp/net-merge install && net-merge tray
```

**Debian, Ubuntu, Linux Mint, Pop!_OS, Raspberry Pi OS** (apt):

```sh
curl -fsSL https://pkg.net-merge.org/apt/key.gpg | sudo tee /usr/share/keyrings/net-merge.gpg >/dev/null
echo "deb [signed-by=/usr/share/keyrings/net-merge.gpg] https://pkg.net-merge.org/apt stable main" | sudo tee /etc/apt/sources.list.d/net-merge.list
sudo apt update && sudo apt install -y net-merge
```

**Fedora, RHEL, Rocky, Alma** (dnf):

```sh
sudo curl -fsSL -o /etc/yum.repos.d/net-merge.repo https://pkg.net-merge.org/rpm/net-merge.repo && sudo dnf install -y net-merge
```

**openSUSE** (zypper):

```sh
sudo zypper addrepo https://pkg.net-merge.org/rpm/net-merge.repo && sudo zypper --gpg-auto-import-keys install -y net-merge
```

**Arch, Manjaro, EndeavourOS** (pacman):

```sh
curl -fsSL https://pkg.net-merge.org/apt/key.asc | sudo pacman-key --add - && sudo pacman-key --lsign-key 0168C7AB77721656904811AE904F61E7F4F1C2A1
printf '\n[net-merge]\nSigLevel = Required\nServer = https://pkg.net-merge.org/arch/$arch\n' | sudo tee -a /etc/pacman.conf
sudo pacman -Sy --noconfirm net-merge
```

**Alpine** (apk):

```sh
sudo wget -O /etc/apk/keys/net-merge.rsa.pub https://pkg.net-merge.org/apk/net-merge.rsa.pub
echo https://pkg.net-merge.org/apk | sudo tee -a /etc/apk/repositories && sudo apk add net-merge
```

**Linux için Homebrew**:

```sh
brew install net-merge/tap/net-merge && sudo setcap cap_net_admin,cap_net_raw+ep "$(readlink -f "$(brew --prefix)/bin/net-merge")"
```

**Diğer tüm Linux** (her CPU için):

```sh
curl -fsSL https://github.com/net-merge/net-merge/releases/latest/download/net-merge-linux-$(uname -m).tar.gz | tar -xz -C /tmp net-merge && sudo install -m 755 /tmp/net-merge /usr/local/bin/ && ...
```

**Windows manuel kurulum**: [net-merge-setup.exe](https://github.com/net-merge/net-merge/releases/latest/download/net-merge-setup.exe)
indirin ve çalıştırın. Windows, uygulama henüz imzalanmadığı için uyarı gösterebilir: *More info* (Daha fazla bilgi), ardından *Run anyway* (Yine de çalıştır) seçeneğine tıklayın.
Ayrıca taşınabilir [zip](https://github.com/net-merge/net-merge/releases/latest/download/net-merge-portable.zip) dosyası da vardır.

Sonra `net-merge tray` komutunu çalıştırın (Linux, macOS) veya Başlat menüsünden başlatın (Windows).
</details>

<details>
<summary><strong>Bilmeniz gerekenler</strong></summary>
<br>

- **Hangi CPU'lar:** x86-64, ARM64 ve Apple Silicon, ARMv7, ARMv6 (Raspberry Pi), x86 32-bit, RISC-V,
  PowerPC (ppc64le), s390x ve LoongArch.
- **Şifre istemez:** Linux paketleri net-merge'e gerekli ağ yetkilerini verir (`setcap`), macOS'ta ise
  `net-merge install` tek bir kural ekler; böylece yalnızca `net-merge tray` komutu root olarak parola olmadan çalışabilir.
- **Linux sistem tepsisi simgesi:** StatusNotifierItem desteği olan masaüstü gerektirir: KDE, XFCE, Cinnamon, LXQt, Budgie
  veya GNOME'de *AppIndicator and KStatusNotifierItem Support* uzantısı.
- **Güvenlik duvarı:** engelliyorsa bilinmeyen trafiği güvene alabilirsiniz (`firewall-cmd --zone=trusted --add-interface=net-merge`).
- **İmzalı depolar:** apt, dnf, zypper ve pacman, [`packaging/apt-signing-key.asc`](packaging/apt-signing-key.asc) dosyasındaki anahtarı kullanır;
  parmak izi `0168 C7AB 7772 1656 9048 11AE 904F 61E7 F4F1 C2A1`.
</details>

## Android

Android için net-merge, Wi‑Fi ve mobil veriyi aynı anda kullanır. Root, hesap ve sunucu gerekmez. Yeni (beta) sürümdür.

1. Telefonunuzda [net-merge-android.apk](https://github.com/net-merge/android/releases/latest/download/net-merge-android.apk) dosyasını indirin.
2. Dosyayı açın ve kurun. Android sorarsa, tarayıcı veya dosya yöneticisine uygulama kurulumuna izin verin.
3. **net-merge** uygulamasını açın, güç düğmesine basın ve VPN isteminde **OK** seçeneğine dokunun.
4. İsteğe bağlı: Hızlı Ayarlar'a **net-merge** kutucuğunu ekleyerek tek dokunuşla açıp kapatabilirsiniz.

Android 8.0 veya üzeri gerekir.

- **Daha hızlı:** aynı anda çok sayıda bağlantı açan uygulamalar, örneğin Play Store güncellemeleri, web sayfaları, torrentler, bulut yedeklemeleri ve indirme yöneticileri. Tek bir büyük indirme, bilgisayarda olduğu gibi tek bir ağda kalır.
- **Mobil veri açık kalır** net-merge çalışırken, veri planınızı takip etmenizde yarar vardır.
- **Bir VPN aynı anda yalnızca bir tane olabilir:** Android yalnızca bir VPN uygulamasının çalışmasına izin verir; bu yüzden net-merge başka VPN yanında çalışmaz.
- **Sorun mu var?** [Sorun bildir](https://github.com/net-merge/net-merge/issues/new/choose) ve *Android* seçeneğini işaretleyin.
  Kod, [net-merge/android](https://github.com/net-merge/android) içinde yer alır.

## Kaldırma

**macOS ve Linux**: terminale şunu yapıştırın. net-merge'i durdurur ve kurulum yöntemine göre (Homebrew, apt, dnf, zypper, apk, pacman veya indirme) kaldırır; ilgili depo ve anahtarı da temizler.

```sh
curl -fsSL https://raw.githubusercontent.com/net-merge/net-merge/main/install.sh | sh -s -- uninstall
```

**Windows**: PowerShell'e şunu yapıştırın veya *Ayarlar > Uygulamalar > Yüklü uygulamalar > net-merge > Kaldır* menüsünü kullanın.

```powershell
& "$env:ProgramFiles\net-merge\net-merge.exe" quit; Start-Process "$env:ProgramFiles\net-merge\unins000.exe" '/SILENT' -Verb RunAs -Wait
```

net-merge durduğu anda ağınız normale döner: sanal adaptörünü ve yönlendirmeleri kaldırır ve hatta bir çökme sonrasında bile çıkar.

<details>
<summary><strong>Kendiniz yazmak istemez misiniz?</strong> Her kurulum yöntemi için ayrı blok.</summary>
<br>

Her blok önce tepsiyi kapatır ve oturum açılışta başlatmayı kapatır, ardından net-merge'i kaldırır.

**Homebrew** (macOS):

```sh
net-merge quit; net-merge autostart off; sudo net-merge uninstall; brew uninstall net-merge && brew untap net-merge/tap
```

**Homebrew olmadan macOS**:

```sh
net-merge quit; net-merge autostart off; sudo net-merge uninstall
```

**Debian, Ubuntu, Linux Mint, Pop!_OS, Raspberry Pi OS** (apt):

```sh
net-merge quit; net-merge autostart off; sudo apt remove -y net-merge && sudo rm -f /etc/apt/sources.list.d/net-merge.list /usr/share/keyrings/net-merge.gpg
```

**Fedora, RHEL, Rocky, Alma** (dnf):

```sh
net-merge quit; net-merge autostart off; sudo dnf remove -y net-merge && sudo rm -f /etc/yum.repos.d/net-merge.repo
```

**openSUSE** (zypper):

```sh
net-merge quit; net-merge autostart off; sudo zypper remove -y net-merge && sudo zypper removerepo net-merge
```

**Arch, Manjaro, EndeavourOS** (pacman):

```sh
net-merge quit; net-merge autostart off; sudo pacman -R --noconfirm net-merge && sudo sed -i '/^\[net-merge\]$/,/^Server = .*net-merge/d' /etc/pacman.conf && sudo pacman-key --delete 0168C7AB77721656904811AE904F61E7F4F1C2A1
```

**Alpine** (apk):

```sh
net-merge quit; net-merge autostart off; sudo apk del net-merge && sudo sed -i -e '\#pkg.net-merge.org/apk#d' -e '\#rohit267.github.io/net-merge/apk#d' /etc/apk/repositories && sudo rm -f /etc/apk/keys/net-merge.rsa.pub
```

**Linux için Homebrew**:

```sh
net-merge quit; net-merge autostart off; brew uninstall net-merge && brew untap net-merge/tap
```

**Diğer tüm Linux** (indirme):

```sh
net-merge quit; net-merge autostart off; sudo rm -f /usr/local/bin/net-merge
```

**Windows taşınabilir zip**: klasöründe `net-merge.exe autostart off` çalıştırın, ardından tepsiyi kapatın ve klasörü silin.

**NixOS**: yapılandırmanızdan `programs.net-merge` (ve `net-merge` girişi) çıkarın ve yeniden derleyin.
</details>

### NixOS

```nix
# flake.nix
inputs.net-merge.url = "github:net-merge/net-merge";

# configuration.nix (with `inputs` passed via specialArgs)
imports = [ inputs.net-merge.nixosModules.default ];
programs.net-merge = {
  enable = true;
  autostart = true;   # optional: start the tray in every graphical session
};
```

Kurulum yapmadan denemek için: `sudo nix run github:net-merge/net-merge -- run`

## İkinci bağlantı ekleme

net-merge için en az **iki gerçek bağlantı** gerekir. Wi‑Fi'ye ek olarak bunlardan birini kullanın: telefon (USB tethering veya hotspot), Ethernet kablosu veya ikinci Wi‑Fi. Takıldığında net-merge birkaç saniye içinde onu ekler.
Bağlantı çıkarıldığında, trafik diğer bağlantılara geçer.

**Windows ve Linux:** telefonu takın ve *USB tethering* (Android) veya *Personal Hotspot* (iPhone) özelliğini açın. Hepsi bu kadar.

**Mac ile iPhone** (ek kurulum gerekmez)
1. iPhone'u kabloyla takın. Sorulursa iPhone üzerinde *Trust* (Güven) seçeneğine dokunun.
2. iPhone üzerinde *Ayarlar > Kişisel Erişim Noktası* bölümünü açın ve *Başkalarının Katılmasına İzin Ver* seçeneğini açın.
3. Mac'te **iPhone USB** ağı görünür. net-merge bunu birkaç saniye içinde ekler.

**Mac ile Android telefon** (uygulama **TetherKit** gerekir)

macOS, Android USB tethering'i kendi başına desteklemez. **TetherKit** uygulaması bu desteği ekler.
1. TetherKit'i kurun ve açın.
2. Telefonu takın ve telefon ayarlarında *USB tethering* özelliğini açın.
3. TetherKit'te **Apply** (Uygula) düğmesine tıklayın. net-merge yeni ağı birkaç saniye içinde ekler.

> **Önce net-merge'i başlatın, sonra Android telefonunu bağlayın.** macOS, net-merge her başlatıldığında veya kapatıldığında TetherKit bağlantısını keser.
> Duraklatma ve sürdürme güvenlidir: net-merge duraklatıldığı sırada sanal adaptörünü korur.
> Telefon bağlantısı kaybolursa TetherKit'te **Apply** düğmesine tekrar basın. iPhone etkilenmez.

Telefonun mobil verisini kullanır; net-merge çalışırken trafiğin bir kısmı telefon üzerinden gider. İstemiyorsanız net-merge'i kapatın.

## Kullanım

1. net-merge'i başlatın. Tepsi simgesi görünür (Mac'te menü çubuğu).
2. Simge **yeşil** ise birleştirme açıktır, **gri** ise duraklatılmıştır.
3. **Kendi kendine duraklatır** iki bağlantıdan azı internet erişimine sahip değilse; çünkü birleştirecek bir şey yoktur ve menü *Paused: one connection* (Duraklatıldı: tek bağlantı) yazar. İkinci bağlantı çalışmaya başladığında tekrar **kendi kendine başlar**. Kendi başlatırsanız veya duraklatırsanız, sizin tercihiniz geçerlidir; duraklatıldıktan sonra otomatik olarak yeniden başlamaz. Menüden *Pause when there is only one connection* (Yalnızca tek bağlantı varken duraklat) işaretini kaldırın veya `net-merge tray -auto-pause=false` çalıştırın.
4. **Simgenin üzerine gelin** her bağlantının ve toplam hızın değerini görün.
5. **Sağ tıklayın** (Mac'te tıklayın) menüyü açmak için. Menü, her bağlantının hızını, net-merge'in kaç bağlantı verdiğini ve *Pause merging* / *Start merging* ile *Quit* düğmelerini gösterir. *Quit* üstündeki satır, çalıştığınız sürümdür; örneğin `v0.3.3`. GitHub'dan en yeni sürüm numarasını okur (başlangıçta ve her 6 saatte bir) ve yeni sürüm varsa `Update to v0.3.4` olur; buna tıklarsanız sürüm sayfası açılır. Bir bağlantıya hız limiti koyabilirsiniz: 1, 2, 5, 10, 20, 50 veya 100 Mbit/s (veya *Unlimited*). Başka bir hız için terminalden: `net-merge limit "Ethernet 2" 25` (Mbit/s; 0 veya `unlimited` limiti kaldırır), `net-merge limit` ise ayarlanan değerleri listeler. Limit, indirme ve yükleme trafiğini kapsar ve yeniden başlatıldıktan sonra da hatırlanır. Yalnızca net-merge'in aktardığı trafik sınırlandırılır: doğrudan adaptöre bağlanmış bir uygulama (ör. sabit arayüzde çalışan qBittorrent) limiti görmez.
6. Oturum açılışta başlatmak için menüden *Start at sign-in* (Oturum açılışta başlat) işaretleyin (veya Windows kurucusunda kutucuğu işaretleyin, veya `net-merge autostart on` çalıştırın). Mac'te bunun için bir kez `sudo net-merge install` gerekir.

İpuçları:
- Torrent istemcileri zaten tüm bağlantıları kullanır. qBittorrent'ın ağ arayüzünü *Any interface* (Herhangi bir arayüz) olarak bırakın.
- **Daha hızlı tarayıcı indirmeleri.** Tarayıcı bir dosyayı tek bir bağlantı üzerinden indirir; bu yüzden tek bir bağlantı kullanır. Chrome, Edge, Brave ve diğer Chromium tabanlı tarayıcılar bunu birkaç bağlantı üzerinden bölerek yapabilir:
  1. `chrome://flags/#enable-parallel-downloading` adresini açın (Edge için: `edge://flags/#enable-parallel-downloading`, Brave için: `brave://flags/#enable-parallel-downloading`).
  2. *Parallel downloading* (Paralel indirme) seçeneğini *Enabled* (Etkin) yapın ve *Relaunch* (Yeniden başlat) düğmesine basın.

  Firefox'ta böyle bir ayar yok; büyük dosyalar için `aria2c -x 8 -s 8 <link>` gibi bir indirme yöneticisi kullanın.
  Bölme yalnızca sunucu dosyanın parçalarını indirmenize izin veriyorsa faydalıdır; çoğu büyük indirme sitesi bunu destekler.
- *Use all adapters (IPv6 only if every adapter has it)* (Tüm adaptörleri kullan, IPv6 yalnızca tüm adaptörlerde varsa) seçeneğini açık bırakın. Sadece IPv6'ya sahip tek bir siteye erişmeniz gerekiyorsa kapatın.
- `net-merge list`, hangi bağlantıların kullanıldığını ve diğerlerinin neden atlandığını gösterir. `net-merge status` canlı sayıları gösterir.

## Sorun giderme

<details>
<summary><strong>İkinci bağlantı daha hızlı yapmıyor</strong></summary>
<br>

Yalnızca her bağlantı kendi yoluyla internete erişebildiğinde hız kazanırsınız. Ev yönlendiricinizdeki Wi‑Fi ile telefonun mobil verisi birlikte çalışır. **Aynı yönlendiriciye** bağlı Wi‑Fi ve Ethernet aynı internet hattını paylaştığı için toplam hız değişmez.

Ayrıca tek bir bağlantı her zaman tek bir bağlantıyı kullanır. Hızlandıran şey çok sayıda paralel bağlantıdır (Steam, tarayıcılar, indirme yöneticileri). `net-merge status` ile her bağlantının kaç bağlantı taşıdığını görebilirsiniz.
</details>

<details>
<summary><strong>VPN açıkken hiçbir şey yapmıyor</strong></summary>
<br>

Bilgisayarınızdaki bir VPN uygulaması (ProtonVPN, NordVPN ve diğerleri) tüm internet trafiğinizi kendi üzerinden gönderir.
net-merge o zaman paylaşacak bir şey bulamaz; bu nedenle daha hızlı bir şey olmaz. VPN'i yalnızca bir bağlantıda kullanmak da güvenli değildir: diğer bağlantı üzerinden giden her şey VPN dışına çıkar.

Çözüm: VPN'i yönlendiricilerde kurup bilgisayardaki VPN uygulamasını kapatın. Çoğu VPN sağlayıcısı yönlendiriciler için rehber sunar. net-merge sonra normal şekilde çalışır ve tüm trafiğiniz yine VPN üzerinden akar.
</details>

<details>
<summary><strong>Linux güncellemesi "404 Not Found" hatası veriyor: rohit267.github.io</strong></summary>
<br>

Paket depoları `pkg.net-merge.org` adresine taşındı. 28 Ekim 2026'dan önce kurulum yaptıysanız ve net-merge'i o günden beri güncellemediyseniz sisteminiz hâlâ eski adrese bakıyor; bu adres yok. Yeni adrese yönlendirin:

```sh
sudo sed -i 's#https://rohit267.github.io/net-merge#https://pkg.net-merge.org#g' $(ls /etc/apt/sources.list.d/net-merge.list /etc/yum.repos.d/net-merge.repo /etc/zypp/repos.d/net-merge.repo /etc/apt/sources.list.d/net-merge.list /etc/yum.repos.d/net-merge.repo)
```

Sonra normal şekilde güncelleyin (`sudo apt update`, `sudo dnf upgrade`, `sudo zypper refresh`, `sudo apk update` veya `sudo pacman -Sy`).
</details>

<details>
<summary><strong>Bir bağlantı görünmüyor</strong></summary>
<br>

`net-merge list` komutunu çalıştırın. Hangi bağlantıların kullanıldığını ve diğerlerinin neden atlandığını gösterir; örneğin "no default gateway" (varsayılan ağ geçidi yok, yani bağlantı henüz internet erişimine sahip değil).

- **Mac'te iPhone:** takın, *Trust* seçeneğine dokunun ve *Ayarlar > Kişisel Erişim Noktası > Başkalarının Katılmasına İzin Ver* seçeneğini açın. *System Settings > Network* içindeki **iPhone USB** ağ hala etkin değilse, **Disable unless needed** (Gerekmedikçe kapat) anahtarını kapatın.
- **Mac'te Android:** **TetherKit** kurun ve **Apply** düğmesine basın (yukarıda açıklandı).
- **Windows'ta telefon:** telefon *Ağ Ayarları* içinde görünmüyorsa, telefon üreticisinin USB sürücüsünü kurun.
</details>

<details>
<summary><strong>Android bağlantısı Mac'te kayboluyor</strong></summary>
<br>

macOS, net-merge her başlatıldığında ve kapatıldığında TetherKit bağlantısını düşürür (duraklatma ve sürdürme güvenlidir).
Önce net-merge'i başlatın, ardından telefonu bağlayın. Kaybolursa TetherKit'te **Apply** düğmesine tekrar basın.
</details>

<details>
<summary><strong>Windows yalnızca tek bir ağ kullanıyor</strong></summary>
<br>

Windows, Ethernet takıldığında Wi‑Fi'yi kapatabilir. Grup İlkesi Düzenleyicisini açın (`gpedit.msc`),
*Computer Configuration > Administrative Templates > Network > Windows Connection Manager* bölümüne gidin ve
**Minimize the number of simultaneous connections to the Internet or a Windows domain** (İnternet veya Windows alanına eş zamanlı bağlantı sayısını en aza indir) ayarını **Disabled** (Kapalı) yapın.
</details>

<details>
<summary><strong>macOS net-merge'i açamıyor veya Windows "protected your PC" diyor</strong></summary>
<br>

Uygulamalar henüz kod imzalanmadı. macOS'ta `xattr -d com.apple.quarantine net-merge` çalıştırın. Windows'ta *More info* (Daha fazla bilgi), ardından *Run anyway* (Yine de çalıştır) seçeneğine tıklayın.
</details>

<details>
<summary><strong>Menü "Paused: one connection" (Duraklatıldı: tek bağlantı) diyor</strong></summary>
<br>

net-merge, internet erişimi olan iki veya daha fazla bağlantı olmadıkça iş yapmaz; bu yüzden bekler. İkinci bağlantıyı takın veya bağlayın ve birkaç saniye sonra otomatik başlar.
Yine de birleştirmek için *Start merging* seçeneğini belirleyin (o zaman ikinci bağlantı gelene veya gidenene kadar açık kalır), veya
*Pause when there is only one connection* işaretini kaldırın.

Birleşimin açılması veya kapatılması, o anda açık olan bağlantıları keser; bu yüzden hiçbir şey hareket etmezken 10 saniye bekler (devam eden bir indirme veya yükleme varsa 2 dakika) ve yeniden başlarken 3 saniye bekler; kendiliğinden asla 30 saniyeden fazla aralıkla geçiş yapmaz.
</details>

<details>
<summary><strong>Tepsi simgesini bulamıyorum</strong></summary>
<br>

Windows'ta simge saat yanındaki `^` okunun arkasında olabilir. macOS'ta menü çubuğundadır. Linux'ta masaüstünün StatusNotifierItem desteği olmalıdır (KDE, XFCE, Cinnamon, LXQt, Budgie veya GNOME'de *AppIndicator and KStatusNotifierItem Support* uzantısı).
</details>

<details>
<summary><strong>Bir site beni tekrar giriş yapmaya zorluyor</strong></summary>
<br>

net-merge her bağlantı için farklı IP kullanabilir; bazı siteler oturum açmanızı tek bir IP'ye bağlar. Bu, bağlantıları birkaç bağlantı arasında bölmenin bir kısıtlamasıdır.
</details>

## Komutlar

```sh
net-merge tray            tepsi ikonu (normal kullanım)
net-merge on | off        çalıştır / duraklat
net-merge quit            tepsiyi kapat ve duraklat
net-merge status | list   canlı değerler / hangi bağlantılar kullanılıyor
net-merge autostart on|off|status
net-merge socks           127.0.0.1:1080 üzerinde sade SOCKS5 proxy (yönetici gerektirmez, uygulama bazlı)
net-merge cleanup         çökme sonrası artan yönlendirmeleri temizler
net-merge install         yalnızca macOS: `sudo net-merge install` (yukarıda açıklandı)
```

Daha fazla bayrak ve ayrıntı için [docs/DEVELOPING.md](docs/DEVELOPING.md) dosyasına bakın.

## Bilmeniz gerekenler

- Yönetici izni gerekir (Windows), `CAP_NET_ADMIN` (Linux) veya bir kez `sudo net-merge install` (macOS).
- Bazı siteler oturumunuzu tek bir IP'ye bağlar. net-merge her bağlantı için farklı IP kullanabilir; bu nedenle bu tür bir site sizden tekrar giriş yapmanızı isteyebilir.
- Bağlantılarınızın IPv6 desteği farklıysa, yalnızca IPv6 olan sitelere erişilemezken yukarıdaki kutu işaretliyse erişilemez.

## Daha fazla

- Her sürümdeki değişiklikler: [CHANGELOG.md](CHANGELOG.md)
- Yeni sürümler her hafta, bir değişiklik olduğunda çıkar. Önemli düzeltmeler hemen yayınlanır.
- Nasıl çalışır, kaynak koddan nasıl derlenir, testler: [docs/DEVELOPING.md](docs/DEVELOPING.md)
- Yardım etmek ister misiniz? [CONTRIBUTING.md](CONTRIBUTING.md). Güvenlik sorunu mu buldunuz? [SECURITY.md](SECURITY.md)
- Lisans: MIT, bkz. `LICENSE`. Üçüncü taraf bileşenler: `THIRD-PARTY-NOTICES.md`.

## Destek

net-merge ücretsizdir. Eğer size zaman kazandırıyorsa [buy me a coffee](https://buymeacoffee.com/rohit267) veya [PayPal ile bağış yapabilirsiniz](https://paypal.me/champdev). Teşekkür ederim!

Kolej projeniz mi var? [DormHost](https://dormhost.dev/?utm_source=net-merge&utm_medium=readme-support),
benim de hazırladığım bir hizmet: Node.js, Python veya Docker ile bir veritabanı, 30 gün ücretsiz.

## English

İngilizce orijinal README içeriği uyumluluk için korunur. Türkçe özet ve üst düzey bölümler bu depodaki varsayılan görünümüdür.
