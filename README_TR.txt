WikiRider

Komut istemcisinden direkt bir Wikirun yapabilirsin (Linux veya MacOS kulland���n� varsay�yorum).

Kurulum
Debian kulland���m i�in, sadece Debian temelli s�r�mler i�in kurulum ad�mlar�n� yazd�m.

#Repoyu kopyala
git clone git@github.com:sadboyzvone/wikirider.git
#Sanal ortam� kur
sudo pip install virtualenv
#Bir adet sanal ortam yarat
cd wikirider && virtualenv .
#Sanal ortam� aktive et
source bin/activate
#Gerekli i�eri�i kur
pip install -r requirements.txt
#�al��t�r
python main.py

SIK�A SORULAN SORULAR
==> Wikirun nedir?
	https://www.urbandictionary.com/define.php?term=Wikirun
==> Bu, XYZ OS �zerinde �al���r m�?
	E�er OS �zerinde python kuruluysa, b�y�k olas�l�kla �al��acakt�r.