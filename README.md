# 🎵 **One Tree System v1.0 — The Ultimate Music Library**

## **Introduction**

The **One Tree System v1.0** is a **unique, ultra-clean structure** to manage all your music, DJ sets, compilations, and music-related videos.
It is designed to **maximize simplicity**, **eliminate duplicates**, and provide an **exceptional user experience**, while remaining compatible with any music or library software (MusicBee, MediaMonkey, Plex, iTunes, etc.).
---
### For the French version of this guide, see [README_FR](README_FR.md).
---

## **Core Principles**

1. **Single Physical Folder: `/MUSIC`**
   All your library is contained in a **single tree**, avoiding duplicates and confusion.

2. **Logical Separation:**

   * `_SYSTEM` → Incoming files, sorting, and verification
   * `_AUDIO` → Clean audio library (Albums, Singles, Live Sets)
   * `_VIDEO` → Festivals, clubs, aftermovies
   * `_META` → Artwork, lyrics, and metadata files

3. **Staging Process:**

   ```
   _Incoming → _ToTag → _Processed
   ```

   * `_Incoming`: recently downloaded files
   * `_ToTag`: files to tag / rename
   * `_Processed`: validated files, ready for the library

4. **Zero Duplicates:**
   Metadata + clear folder separation ensure each file is unique and properly indexed.

---

## **Folder Structure**

```
/MUSIC
    /_SYSTEM
        /_Incoming
        /_ToTag
        /_Processed
        /_Rejected
        /_Backups
        /_Logs
    /_AUDIO
        /Artists
        /Compilations
        /Live & Sessions
        /Unsorted
    /_VIDEO
        /Festivals
        /Clubs
        /Aftermovies
        /Interviews
    /_META
        /Artwork
        /Lyrics
        /Info
        /TagsBackup
```

---

## **Recommended Workflow**

1. **Download / Import:**
   Place all new files in `/MUSIC/_SYSTEM/_Incoming`.

2. **Verification & Tagging:**

   * Move files to `_ToTag`
   * Tag with MusicBrainz / Picard / MusicBee
   * Rename using:

     ```
     Artist - Title (Year) [Format]
     ```

3. **Validation:**

   * Move tagged files to `_Processed`
   * Organize into `_AUDIO` by type (Singles, Albums, Live Sets)

4. **Index in Software:**

   * Scan `_AUDIO` in your music software
   * Enjoy automatic views: genre, year, BPM, label, format

5. **Ongoing Maintenance:**

   * `_Rejected`: corrupted or low-quality files
   * `_Backups`: tag and artwork backups
   * `_Logs`: import history for audit

---

## **Advantages of One Tree System v1.0**

* **Extreme simplicity:** only one base folder
* **Eliminates duplicates** via metadata and staging
* **Software-friendly:** works with MusicBee, MediaMonkey, Plex, iTunes, etc.
* **Flexible:** easy to add categories or new formats
* **Scalable:** works for hundreds or hundreds of thousands of files
* **Clean visual hierarchy:** every folder has a precise role

---

## **Recommendations**

* Use an **indexing software** (MusicBee, MediaMonkey, Plex) to generate views:
  Genre, BPM, Year, Format, Artist, Album, Singles
* Keep `_SYSTEM` for new incoming files
* Backup `_META` to avoid losing tags or artwork

---

## **Conclusion**

The **One Tree System v1.0** transforms music library management into a **clean, organized, and scalable experience**, perfect for audiophiles, DJs, collectors, and music enthusiasts.
It allows you to **find, play, and share your music instantly**, maintaining a library that is **intelligent and future-proof**.
