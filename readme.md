# grqa

>**Narrated Ibn `Abbas:**
>
>***The Prophet (ﷺ) embraced me and said, “O Allah! Teach him (the knowledge of) the Book (Qur’an).”***
>
>*Sahih al-Bukhari 7270*

*grqa* (short for "Get Random Qur'an Ayat) is a small program that allows you to fetch random verses from the Qur'an in your terminal. There are two instances, one written in bash (compatible with v. 3.2 and up) and one Python2/3 compatible instance.

### Installation

Dependencies: wget, bash, su, chmod, python (if using gqra-py)

```bash
su
cd /usr/bin
wget https://raw.githubusercontent.com/zamiur/grqa/master/gqra (or gqra-py)
chmod +x grqa (or gqra-py)
```

Optional step (If you don't want this just continue as usual with the `wget` command)

```bash
vi gqra (or gqra-py) # Edit the "cd /usr/bin" line to the directory of moshaf
wget https://raw.githubusercontent.com/zamiur/grqa/master/quran.txt
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

Ideas considered *["feature-creep-esque"](https://en.wikipedia.org/wiki/Feature_creep)* (I might make a whole new program for these)

- Implement recitation
- Fetch information and show meanings/definition*

***Ideas that could be implemented***

- Get specific Qur'an ayat (for example `grqa 1 5` will print out ayat 5 of Surah Fatiha)
- Fetch information and show meanings/definition*
- Check if moshaf (`quran.txt`) exists, if not download again.

<p style="font-size: small;">*As to how much information should be necessary before it can be considered more of a feature creep</p>

### Changelog

1.0.0 - Initial build (Both bash and python)

1.0.1 - Patch to fix `shuf: ./quran.txt: No such file or directory`.  By default, the Qur'an moshaf is stored in `/usr/bin`. Optionally the user can edit the directory line and set a custom directory where the moshaf is located. 

---

### External Resources

[The Quranic Arabic Corpus](http://corpus.quran.com/)

[Tanzil (source for quran moshaf in txt form)](http://tanzil.net/)

[Al Quran KSU Electronic Moshaf](https://quran.ksu.edu.sa/index.php?l=en#aya=1_1&m=hafs&qaree=husary&trans=en_sh)

