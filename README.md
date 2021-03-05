# This repo contains world country list of 186 countries, their 3-digit ISO codes and their currencies
The file is named <b>ctr_lst_iso_cc.txt</b><br>
Each line contains COUNTRY_NAME | 3_DIGIT_ISO_CODE | CURRENCY<br>
Example: Malawi|mwi|mwk<br>
The list will also contain the country's dial code and will be updated with an accompanying folder with each country and its flag.<br>
You can then use some regular expressions to extract each token {country name, 3-digit ISO and currency} since each token is separated by '|'<br>
