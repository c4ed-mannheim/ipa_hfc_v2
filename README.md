# ipacheck

IPA has recently (in 2022) released version 3 and 4 of the high-frequency checks packages. I've put up version 2 here so that you can easily install the older version.

## Installation

```Stata
* ipacheck may be installed directly from GitHub
net install ipacheck, ///
    from("https://raw.githubusercontent.com/c4ed-mannheim/ipa_hfc_v2/main/ado") ///
    replace 


* after initial installation ipacheck can be updated at any time via
ipacheck update

* fresh copies of the supplementary do-files, Excel inputs, etc. are available via
ipacheck new

* to verify you have the latest versions of the commands
ipacheck version
```

