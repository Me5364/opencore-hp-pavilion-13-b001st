# opencore-hp-pavilion-13-b001st monterey

opencore monterey efi file for hp pavilion 13 b001st laptop

CPU:i5-4210U

GPU:intel hd Graphics 4400

Network:Qualcomm Atheros QCA9565/AR9565

# notes:

you need change serial number/mlb/systemUUID/rom to apple services work

at boot (and waking up from sleep) laptop is goign to lag for about 15 seconds

if adjusting screen brightness is not working do the steps under.

1-)make your laptop go to sleep for 2 seconds

2-)wake up from sleep(this should fix the issue)

no drm

no bluetooth

in macos recovery wifi does not work

# How to get wifi working

after installing macos download and install the opencore legacy patcher from https://github.com/dortania/Opencore-Legacy-Patcher/releases this link

after installing opencore legacy patcher open it and do root patches (after doing this updates are going to be a lot more larger)

after doing root patches now wifi card can scan networks

to connect to internet using wifi click to wifi icon click to other and type your wifi name and password manually

note: there is a bug that always wifi icon always shows you are very away from wifi

# Türkçe
hp pavilion 13-b001st laptop için macos monterey opencore efi klasörü

CPU:i5-4210U

GPU:intel hd Graphics 4400

Network:Qualcomm Atheros QCA9565/AR9565

notlar:

config.plistteki platformInfo daki serial number/mbl/rom ve systemuuid kısımlarını sizin doldurmanız gerekiyor

her laptobu açtığınızda (ve uykudan uyandığında) 15 saniyelik bir lag olacaktır

eğer ekran parlaklığını ayarlama çalışmıyorsa aşapıdaki adımları izleyiniz

1-) laptobunuzu uyku moduna 2 saniyeliğine alınız

2-) laptobu uykudan uyandırınız

drm desteklenmez

bluetooth desteklemez

macos recoverysinde wifi çalışmaz

wifiyi çalışır hale getirmek için aşağıdaki adımları izleyiniz:

ilk önce macos kurunuz ve https://github.com/dortania/Opencore-Legacy-Patcher/releases bu linkten opencore legacy patcher'ı indirip kurunuz

oclp'de (opencore legacy patcher)  root pachlerini yapınız (bundan sonra güncelllemeler çok daha büyük olacaktır

root patchini yaptıktan sonra wifi ağları görmeye başlayacaktır

wifiye bağlanmak için wifi iconuna tıklayın ardından other (yada diğer Yada diğer ağlar) butonuna tıklayın burada wifi adını ve şifresini manuel olarak giriniz we wifiye bağlanacaksınız

not: wifi her zaman bir bug'dan dolayı bir tık olarak gözükür.

