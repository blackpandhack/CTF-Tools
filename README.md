Outils pour CTF
===============

### LIENS UTILES :
 - https://github.com/ctfs/write-ups-2016
 - https://github.com/p4-team/ctf/tree/master/2016-04-01-nuitduhack-quals
 - https://github.com/hexpresso/WU-2016/tree/master/nuit-du-hack-ctf-quals-2016
 - https://www.dailysecurity.fr/write-up-ndh-quals-2016-spacesec
 - https://www.asafety.fr/?s=CTF+NDH+2016
 - https://0x90r00t.com/fr/2016/04/04/nuit-du-hack-quals-2016-web-100-find-me-im-famous-write-up
 - https://blog.0daylabs.com/2016/04/03/unserialize-php-object-injection
 - https://securite.intrinsec.com/2016/04/03/write-up-nuit-du-hack-2016-ctf-quals-matriochka-step-4
 - https://ungeek.fr/ctf-nuit-du-hack-2k16
 - https://wiki.zenk-security.com/doku.php?id=ndh_2016_quals
 - https://0xabe.io/ctf/exploit/2016/04/03/Nuit-du-Hack-pwn-Secure-File-Reader.html
 - https://wiremask.eu/writeups/nuit-du-kack-quals-2016-secure-file-reader
 - http://vulnerablespace.blogspot.fr/2016/04/ctf-writeup-nuit-du-hack-ctf-quals-2016.html
 - http://blog.security-x.fr/2013/03/18/analyse-dun-ransomware-avec-volatility

### Tools and Resources to Prepare for a Hacker CTF Competition or Challenge :
 - http://resources.infosecinstitute.com/tools-of-trade-and-resources-to-prepare-in-a-hacker-ctf-competition-or-challenge

### A curated list of CTF frameworks, libraries, resources and softwares :
 - https://github.com/apsdehal/awesome-ctf

### Capture the Flag: Security Tools and Sites :
 - http://faculty.cs.nku.edu/~waldenj/ctf/tools.html

### THEME: FORENSIC
1. **Decompilers Online**
 - Ce site permet de décompiler en ligne des fichiers APK (Application Android) ainsi que des fichiers java.
 - http://www.javadecompilers.com
2. **IDEONE**
 - IDE en ligne permettant de compiler un grand nombre de langages de programmation (C, Java, C++, PHP…).
 - https://ideone.com
3. **Malwr**
 - Il s'agit d'un système d'analyse fonctionnant en mode Sandbox et capable de tracer les appels aux API et fonctions Windows, de connaitre et conserver les fichiers créés ou supprimés par le malware, d'enregistrer les états de la mémoire (dump) lors de l'infection, de choper les trames réseaux générées par la machine (domaines contactés, IP..etc.), et même de faire des captures-écrans durant l'exécution du malware.
  - https://malwr.com
4. **Volatility**
  - Volatility est un Framework contenant de multiples outils visant à aider dans la manipulation de données contenues dans un dump mémoire (RAM). A ce jour, l’outil permet d’extraire les données suivantes : Processus en cours d’exécution, connexion ouvertes, DLLs chargées par les processus, fichier ouverts par les processus, exécutables, données de la base de registre…
  - http://www.lestutosdenico.com/tutos-de-nico/forensique-analyse-memoire-volatility

 

### THEME : BRUTE FORCE
1. **John The Ripper**
 - Utile pour bruteforcer des mots de passes divers (Windows, fichier ZIP…).
 - [tutorial](http://mpslinux.com/petit-tutoriel-simple-sur-lutilisation-de-john-the-ripper)

### Lignes de commande utile :
1. **John the ripper**
```bash
zip2john FICHIER.zip > bruteforce/zip.hashes
john --show ./zip.hashes
```
2. **Hashcat**
  [dico](http://fhack.troptop.net/?BruteForce_%26amp%3B_Rainbow_%26amp%3B_Dico___Outils___Hashcat)
```bash
# Hashcat est le plus rapide outil de récupération de mot de passe à base de CPU dans le monde pour bruteforcer les fichiers protégés.
./hashcat-cli64.bin -a0  -m0 hashfile ../../wordlists/darkc0de.lst
```
3. **Android Hash to gesture**
  - Outil en ligne permettant d’afficher la gestuelle d’un écran de verrouillage Android à partir d’un dump d’un HASH récupéré sur le téléphone.
  - https://barney.0x539.se/android/

### THEME: RESEAUX
1. **Wireshark**
  - Wireshark est un analyseur de paquets libre utilisé dans le dépannage et l'analyse de réseaux informatiques, le développement de protocoles, l'éducation et la rétro-ingénierie.
  - https://www.wireshark.org

 
### THEME : STEGANOGRAPHIE PHOTO
1. **Forensically**
  - Forensically est un site en ligne très pratique pour faire de l’analyse d’image : détection de copie, de pixels modifiés, d’erreurs, analyse de bruit…
  - https://29a.ch/photo-forensics/#forensic-magnifier

### THEME : STEGANOGRAPHIE AUDIO
1. **Audacity**
  - Logiciel gratuit pour analyser des trames audio
  - http://www .audacity.fr
2. **Sonic Visualizer**
  - Logiciel gratuit sous Linux, Windows et Mac OS X permettant de faire de l’analyse de trame, modifier les spectres…
  - http://www.sonicvisualiser.org
