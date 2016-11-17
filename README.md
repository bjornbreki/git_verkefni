#Fyrsta Git verkefnið
# Spuringar um git
# Björn Breki
# VSH2B3U
#
1.  a) cd stendur fyrir change directory og það er hægt að slá inn "cd " með bili og slá síðan inn möppu heitið.
	b) cd ~ fer einum til baka, þar að segja einni möppu eða stað nær rótinni.
	c) ls birtir allar möppur og verkefni sem að hægt er að fara inn á með cd.
	d) pwd sýnir í hvaða möppu eða hvar þú ert stadur og ert að vinna í.
	e) mkdir býr til nýja möppu á þeim stað sem að þú ert í möppuni.

2.  a) git clone er eins og það hljómar, þú ert að klóna skránna sem að þú ert með skráða. Eða þú ert að afrita það sem að þú velur eftir á þú skrifar git clone
	b) git log birtir eða sýnir allar stór breytingar eða pull og push sem að hafa átt sér stað.
	c) git status fer yfir skrárnar hjá báðum eða öllum aðilum og birtir það sem er öðruvísi eða github kannast ekki við.
	d) git diff sýnir þér hvaða breytingar hafa átt sér stað á milli verkefna í aðeins meiri smáatriðum en git log.
	e) git checkout skiptir um stöðu sem að notandinn er standur og fer með hann þar sem að hlutirnir byrjuðu.

3.  a) git diff er grunn skipunin en það þarf að slá eitthvað annað inn til að koma einhverju til skila vegna þess það er ekki nóg að sláinn þessa fyrirspurn
	b) git diff --staged sýnir allar breytingar sem að hafa verið gerðar og birtir working tree. Einnig er hægt að slá inn $ git diff --cached
	c) git diff commit1 commit2 sýnir notandanum hvað er öðruvísi á þessa beggja verkefna
	
4. e.version control er hvað er útgáfan gömul og hvaða commends virka og hverjar ekki.

5. GIT er frekar létt forrit eða um það bil 32mb. Git er til fyrir Apple, Linux, Solaris og Windows. GIT er langt frá því að vera flókið í keyrslu, það er um það bil 10 skipanir allt í allt. GIT ei einnig með frábærar lausnir þegar að það kemur að því að nokkrir eru að edit'a sama hlutinn á sama tíma. Mér finnst það fáranlega flott hvernig það er birt með = merkjum og < > merkjum. Síðast en ekki síst þá er setur GitHub .'inn yfir i'ið með því að gef notandinum aðferðir til að edit'a eða búa til nýja hluti eins og möppur eða samsett verkefni með forritunu.

6. Ég held að ég mun gera það í hvert skipti sem að ég mun taka við verkefni til að fá alltaf að sjá hvað er öðruvísi við sitt hvort verkefnið og fundið best leiðina til að blanda þeim saman.

7. Git er byggt upp á þremur skrefum sem að fær verkefnin á milli  
    a) Repository í GIT er fyrsta skrefið og það tekur við því sem að notandinn sló inn og færir það yfir til Working Directory.
    b) Working Directory skref númer tvö og tekur við frá Repository, les yfir verkefnið og atugar hvort að það sé einhver munur á verkefninum og endar á því að senda það yfir til Staging Area til að klára beiðnina sem notandinn sló inn.
    c) Staging area er síðasta skrefið og merkir við þær villur sem að eftir eru frá Working Directory og pakkar svo öllu saman og sendir það síðan að lokum yfir til Repository og bíður þar með eftir annari skipun frá notandanum og endurtekur þar með hringinn.
    
8. Það er sniðugt að nota eitt branch fyrir hvert og eitt verkefni, svo að það sé hægt að sjá hvert og eitt verkefni inn á GitHub.