<p align="center">
  <img src="https://raw.githubusercontent.com/sauceisgood/tg/master/.image/20191203_205322.jpg" width="470" height="150">
</p>

<p align="center"><img src="https://img.shields.io/badge/Version-3.1-brightgreen"></p>
<p align="center">
<a href="https://github.com/sauceisgood">
    <img src="https://camo.githubusercontent.com/a88a4b91e4220651dd5593fc39b3be063a7e53ecd1afc50aa75ac915cedd7c47/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f666f6c6c6f776572732f746833756e6b6e306e3f6c6162656c3d466f6c6c6f77267374796c653d736f6369616c" data-canonical-src="https://img.shields.io/github/followers/sauceisgood?label=Follow&amp;style=social" style="max-width:100%;">
  </a>
</p>
<p align="center">
  Telegram Group Scrapper
</p>
<p align="center">
</p>

---

## • API Setup
* Go to http://my.telegram.org  and log in.
* Click on API development tools and fill the required fields.
* put app name you want & select other in platform Example :
* copy "api_id" & "api_hash" after clicking create app ( will be used in setup.py )

## • How To Install and Use

`$ pkg install -y git python`

`$ git clone https://github.com/sauceisgood/tg.git`

`$ cd tg`

* Install requierments

`$ python3 setup.py -i`

* setup configration file ( apiID, apiHASH )

`$ python3 setup.py -c`

* To Genrate User Data

`$ python3 scraper.py`

* ( members.csv is default if you changed name use it )
* Send Bulk sms To Collected Data 

`$ python3 smsbot.py members.csv`

* Update Tool

`$ python3 setup.py -u`

---

</p>
