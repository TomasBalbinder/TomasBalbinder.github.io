# <ins> Základy GITu</ins>
<p>&nbsp;</p>

### Co dělá Git:
___
* zaznamenává historii vývoje projektu
* dělá zálohy, kopie s metadaty
* ukláda zálohy na disk
<p>&nbsp;</p>


### Co dělá Github:
___
* je místo kam můžeš nahrát svoji aplikaci, svůj kod.
* je veřejný server - cloud 
* funguje bez GITu a naopak
* je to jen jedna z možností
* ukláda zálohy na disk
* je úplně zadarmo

## Práce s gitem:
___ 
**A jak vlastně zjitím jestli mám už git nainstalovaný?**\
Tenhle postup je pouze pro operační systém Windows.

zmáčknětě klavesovou zkratku `win + Q` poté napište **CMD** a zmáčketě `enter`

poté piště již do konzole:\
**git --version** zjistí verzy gitu, pokud nic nevypíše, nemáš ho 
a je třeba ho instalovat [https://git-scm.com/](https://git-scm.com/)

při prvním spuštění je potřeba vytvořit **jmeno** a **email**
pro pozdější synchronizaci s Githubem

```
git config --global user.name “jméno”
git config --global user.email “e-mail”
```
**při vytoření každného nového projektu je potřeba inizializovat složku
ze které bude git nahlížet na soubory**

`git init` - inicializuje adesář

`git status` - ukáže stav v jakém se soubory nachází 


