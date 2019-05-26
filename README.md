# Pasientarmb�nd med tilh�renede mobilapplikasjon

Dette fillageret er kildekode utviklet i sammenheng med et bachelorprosjekt innen Elektronikk ved UiA v�ren 2019 i samarbeid med konsulentselskapet Bouvet.
Tittelen for prosjektet er "Pasientarmb�nd med tilh�rende mobilapplikasjon". 
Her ligger kildekode for en mobilapplikasjon (mso-login) og kildekode for et pasientarmb�nd basert p� en Nordic Semiconductor nRF52832-mikrokontroller (PasArm). 

## Mitt Sykehusopphold (mobilapp)

Kildekoden for mobilapplikasjonen (Mitt Sykehusopphold) ligger i mappen "mso-login". 
1. Det kreves at PC-en har Android Studio for � kunne �pne prosjektet. Android Studio lastes ned fra https://developer.android.com/studio/index.html
2. For � �pne prosjektet b�r Android Studio v�re installert og �pnet p� PC-en. 
3. I Android Studio, trykk p� "File", "Open" og deretter lokaliser "mso-login"-mappen. Trykk deretter p� "OK".
4. La prosjektet bygge en god stund. 

Prosjektet kan testes virtuelt eller p� tilkoplet smartelefon via USB. Smartelefonen m� ha operativssystemet Android (versjon 4.3 Jelly Bean og oppover). 
5. Eventuelt kople til smartelefon via USB. Utviklermodus og "USB-debuggin" m� v�re aktivert p� telefonen. Se f.eks. http://www.lovemediasoft.com/article/no/enable-usb-debugging-on-android-device.html
6. Trykk p� den "Run 'app'" (den gr�nne pilen/trekanten �verst til h�yre) eller trykk "Shift + F10". 
7. Velg enten tilkoplet smartelefon eller bruk virtuell enhet. 
8. Installer n�dvendige SDK-er og programtillegg. Disse oppdager Android Studio automatisk. 

### PasArm (fastvare for mikrokontroller)

Kildekode for pasientarmb�ndet (nRF52832-mikrokontroller) ligger inne i "PasArm"-mappen. 
1. Prosjektet kan �pnes i f.eks. SEGGER Embedded Studio (SES). 
2. SEGGER Embedded Studio b�r v�re installert p� PC-en. SES kan lastes ned fra https://www.segger.com/downloads/embedded-studio
3. Dobbelklikk filen "PasArm_pca10040_s132.emProject" i mappen "mso\PasArm\PasArm\pca10040\s132\ses" for � �pne prosjektet. '
4. For � teste prosjektet p� utviklerkort (nRF52 DK) kan man i SES trykke "Build" i oppgavelinjen �verst og deretter "Build and Run".