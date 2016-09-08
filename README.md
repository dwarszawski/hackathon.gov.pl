# hackathon.gov.pl

## Pomysł

Wykorzystanie zbioru danych https://danepubliczne.gov.pl/dataset/rejestr-produktow-leczniczych oraz danych
udostępnianych przez *U.S. National Library of Medicine* w formie bazy danych LactMed (TOXNET DATABASE) z informacjami o wpływie substancji aktywnych na laktacje i ryzyku związanym z przenikaniem leków do mleka matki w przypadku dzieci karmionych piersią.

Przykład:
lek o nazwie Zoloft zawiera Sertralinum (Sertralina) który jest opisany jako rekord w bazie LactMed w następującej postaci:

	* Krótkie podsumowanie dotyczące stosowania leku podczas laktacji.
	* Opis badań wpływu substancji czynnych na laktacje oraz dziecko karmione piersią. 

[źródło] (https://toxnet.nlm.nih.gov/cgi-bin/sis/search2/f?./temp/~caXSWe:1)

## Informacje uzupełniające

1. Rejestr produktów leczniczych:

	* (plik xls) zawiera nazwy substancji leczniczych w języku łacińskim które można powiązać z bazą LacMed z wykorzystaniem kolumny *synonym*.
	* aktualizowany codziennie.

2. Baza LactMed:

	* LactMed is updated monthly.
	* There is no charge for leasing NLM data
	* Those interested in obtaining NLM data directly from an NLM licensee do not enter into a license agreement with the NLM. Rather, contact the licensee directly.
	* Toxnet RESTful API
	  ```
	   The TOXNET Web Service API is free of charge. Neither registration or licensing is required.
	   If you build an interface using the TOXNET Web Service API, please indicate that the information is from TOXNET for the National Library of Medicine
	  ```
	  [warunki korzystania](https://toxnet.nlm.nih.gov/toxnetapi/TOXNETWebService.html)
3. Źródła
	[Sample reqeuest](https://toxnet.nlm.nih.gov/toxnetapi/search_chemical.html)
	[FAQ](https://toxnet.nlm.nih.gov/newtoxnet/faq.html)
