#TransCasm_Corpus

Bilingual Corpus of Sarcastic Tweets

-SOURCE
 SIGN Coprus (Peled and Reichart, 2017)

- Languages:
	EN>>FR

-Format
	-txt UTF8
	-original format kept as source (EN tweets are normalised)
	-target [FR] keeps the accents
	-a full line consists of a tweet and its interpretation and is displayed between []
	
	- original tweets are displayed between quotations (either double ("") or single ('')) followed by a comma (,) and their interpretation also between quotations. Example: 
	[" due to the large blister on the bottom of my right foot i guess i'm stuck on the couch tomorrow that sucks", 'awesome an excuse to sit on the couch all day']
	[' draymond what a player', ' draymond is not a good player']
	
	- in the source [EN] file, tweets are repeated as many times as their interpretations are displayed. Example:
	[' cant wait until tomorrow', " i'm not looking forwarrd to tomorrow"]
	[' cant wait until tomorrow', ' i can totally wait till tomorrow']
	[' cant wait until tomorrow', " i'm not looking forward to tomorrow"]
	
	- in the target file [FR], the format is kept and tweets are repeated as many times as their interpretations are translated. Example:
	[' j’ai hâte d’être à demain', " je n’ai pas hâte d’être à demain"]
	[' j’ai hâte d’être à demain', ' je peux tout à fait attendre d’être à demain']
	[' j’ai hâte d’être à demain', " je ne suis pas pressé d’être à demain"]


- Corpus Statistics:
	- total number of lines: 1831
	- average number of interpretations translated: 2.4 (it varies from 1-3)

-Topics (including):
		-Weather
		-traffic and transportation
		-work
		-school
		-health
		-sportspolitics
		-social relationships
		
 *tweets are not grouped by topics*

Citation



References



[2]Peled, Lotem; and  Reichart, Roi. "Sarcasm SIGN: Interpreting Sarcasm with Sentiment Based Monolingual Machine Translation." (ACL 2017).
