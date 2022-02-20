# hadiths-json-files
JSON files of entire collections of hadith. Each collection of hadiths in one JSON file each. Still in-progress

## Details
Here is an example:
```
{ 	
        "name": "Sunan Abi Dawud", 
	"arabic_name": "سنن أبي داود",
	"short_desc": "Sunan Abī Dāwūd is a collection of ḥadīth compiled by Imām Abū Dāwūd Sulaymān ibn al-Ash`ath as-Sijistānī (raḥimahullāh). It is widely considered to be among the six canonical collections of ḥadīth (Kutub as-Sittah) of the Sunnah of the Prophet (saws). It consists of 5274 aḥādīth in 43 books.",
	"num_books": "43",
	"num_hadiths": "5274",
	"all_books": [
          ...
          {
            "num": "34",
            "english_title": "Clothing (Kitab Al-Libas)",
            "arabic_title": "كتاب اللباس",
            "hadith_list": [
                ...
                {
                  "title": "Sunan Abi Dawud 4031", 
                  "narrator": "Narrated Abdullah ibn Umar:", 
                  "english_text": "The Prophet (ﷺ) said: He who copies any people is one of them.", 
                  "arabic_text": "حَدَّثَنَا عُثْمَانُ بْنُ أَبِي شَيْبَةَ، حَدَّثَنَا أَبُو النَّضْرِ، حَدَّثَنَا عَبْدُ الرَّحْمَنِ بْنُ ثَابِتٍ، حَدَّثَنَا حَسَّانُ بْنُ عَطِيَّةَ، عَنْ أَبِي مُنِيبٍ الْجُرَشِيِّ، عَنِ ابْنِ عُمَرَ، قَالَ قَالَ رَسُولُ اللَّهِ صلى الله عليه وسلم \n\" مَنْ تَشَبَّهَ بِقَوْمٍ فَهُوَ مِنْهُمْ \" .", 
                  "local_num": "12"
                 },
                ...
            }
            ...
        ]
}
```
As you can see above in, the data is pretty straightforward. The beginning of the JSON file gives the details of the collection of hadiths, then it has a list of all_books which in turn, each book contains a list of hadiths.
