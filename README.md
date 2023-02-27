# Islam Datasets

This GitHub project contains two folders: `quran` and `hadith`. The `quran` folder currently only has the Sahih International translation of the Quran, while the `hadith` folder contains CSV files of hadiths from Bukhari, Muslim, Adab, and Nawawi40 collections. The hadiths were taken from https://sunnah.com.

This dataset was primarily collected for the sake of the [NaseehahBot](https://linktr.ee/naseehahbot), a bot for social media that posts reminders curated to be timely, short, and include only sahih or hasan hadiths. However, this data is available for anyone to use for their own work as long as it furthers the goals of Islam and the sunnah.

## Hadith Folder

The `hadith` folder contains CSV files of Bukhari, Muslim, Adab, and Nawawi40 collections. Each CSV file has the following columns:

- `id`: An id of the hadith, for example, `adab1`.
- `collection`: The book collection it's in, for example, `adab`.
- `bookNumber`: The book number it's in, for example, `1`.
- `bookName`: The book title name, for example, "Al-Adab Al-Mufrad".
- `chapterId`: The chapter the hadith is in, for example, "2".
- `hadithNumber`: The overall hadith number in the book, for example, "22" or "3027b".
- `text`: The hadith text or 'matn'.
- `gradedBy`: If it has a grading other than Bukhari and Muslim such as Adab-al-Mufrad, then who graded it.
- `grade`: The grade for example Sahih or Dai'f.

## Quran Folder

The `quran` folder contains the Sahih International translation of the Quran. Each file has the following columns:

- `surah`: The chapter or surah number.
- `verse`: The verse or ayah number.
- `text`: The text of the ayah.
