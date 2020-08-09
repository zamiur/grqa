# grqa

>**Narrated Ibn `Abbas:**
>
>***The Prophet (ﷺ) embraced me and said, “O Allah! Teach him (the knowledge of) the Book (Qur’an).”***
>
>*Sahih al-Bukhari 7270*

*grqa* (short for "Get Random Qur'an Ayat) is a small program that allows you to fetch random verses from the Qur'an in your terminal. There are two instances, one written in bash (compatible with v. 3.2 and up) and one Python2/3 compatible instance.

### Installation

Dependencies: wget, bash, su, chmod, python (if using gqra-py)

```
su
cd /usr/bin
wget https://raw.githubusercontent.com/zamiur/grqa/master/gqra (or gqra-py)
wget https://raw.githubusercontent.com/zamiur/grqa/master/quran.txt
chmod +x grqa (or gqra-py)
exit
```

### Usage

You can run it by typing `grqa` or`grqa-py` anywhere

Example output:

```
zamiur@ayylmao:/usr/bin$ grqa
44|32|وَلَقَدِ اخْتَرْنَاهُمْ عَلَى عِلْمٍ عَلَى الْعَالَمِينَ
zamiur@ayylmao:/usr/bin$
```

### License

This program is freeware and should be treated as public domain.

### Future Plans (possibly)

- Get specific Qur'an ayat
- Fetch information and show meanings/definition
- Implement recitation

---

### External Resources

[The Quranic Arabic Corpus](http://corpus.quran.com/)

[Tanzil (source for quran moshaf in txt form)](http://tanzil.net/)

[Al Quran KSU Electronic Moshaf](https://quran.ksu.edu.sa/index.php?l=en#aya=1_1&m=hafs&qaree=husary&trans=en_sh)

