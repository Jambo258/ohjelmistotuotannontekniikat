# Robot Framework git-harjoitus

## Käyttöönotto

### Vaatimukset

* Python 3.7 ->
* Google Chrome -verkkoselain

### Alkutyö

* Kloonaa tai lataa tämä repo johonkin kansioon, ja avaa tämä kansio

### *vaihtoehtoinen Windowsilla* Virtuaaliympäristö

1. Asenna virtualenv - ```pip install virtualenv```
2. Luo ympäristö - ```virtualenv rf-env```
3. Aktivoi ympäristö
    * *Powershell* suorita PowerShell pääkäyttäjänä, ja aja
      * ```cd <reitti-ladattuun-kansioon>```
      * ```set-executionpolicy RemoteSigned``` Vaatii pääkäyttäjäoikeudet
      * ```.\rf-env\Scripts\activate.ps1```
    * *CMD* 
      * ```rf-env\Scripts\activate.bat```
    * *Bash*
      * ```source rf-env/bin/activate```
4. Komentorivi on nyt virtuaaliympäristössä
   
### Asennus

1. Asenna vaaditut kirjastot - ```pip install -r requirements.txt```
2. Asenna selaimen webdriver - ```webdrivermanager chrome```
3. Aja ohjelma - ```robot swag.robot```