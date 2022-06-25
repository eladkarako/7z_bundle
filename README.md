<h1>7z_bundle</h1>

<h3>

https://github.com/eladkarako/7z_bundle/raw/master/x86.zip  

https://github.com/eladkarako/7z_bundle/raw/master/amd64.zip  

https://github.com/eladkarako/7z_bundle/raw/master/arm64.zip  

</h3>


<hr/>

current version is

- <a href="https://www.7-zip.org/download.html">7-Zip 22.00 (June 15th, 2022)</a>.
- Codecs <a href="https://github.com/mcmilk/7-Zip-zstd/releases/tag/v21.03-v1.5.0-R2">7-Zip ZS 21.03 - v1.5.0 - Release 2 (October 6th, 2021)</a>.


<hr/>

a bundle of the most recent official 7zip (https://www.7-zip.org/download.html)  
and most recent ZSTD codecs (https://github.com/mcmilk/7-Zip-zstd)  
+ Windows 11 compatible patches.

patches (https://github.com/eladkarako/manifest) include:
- manifest (DPI awareness, long path awareness, segmented heap, compatibility).
- set large address aware.

additional reg files (under 'resources'): 
- UI defaults.
- extra cleanup (after uninstallation).

7-Zip Extra included:  
- based on original version (since it is newer and less buggy), so no codec support.
- no arm64, just x86 and x64 (amd64).
- no FAR plugin (since no point in patching it, you can just download the original extra package from the original website).

<details><summary>content (example)</summary>


- non functional files (license, text, chm) moved to 'resources' folder.
- lang folder moved to 'resources' folder as well. if you need multi-language support, move it back to main folder.


```txt
/
|   7-zip.dll
|   7-zip32.dll
|   7z.dll
|   7z.exe
|   7z.sfx
|   7zCon.sfx
|   7zFM.exe
|   7zG.exe
|   7za.exe
|   7za.dll
|   7zxa.dll
|   
+---Codecs
|       brotli-x64.dll
|       flzma2-x64.dll
|       lizard-x64.dll
|       lz4-x64.dll
|       lz5-x64.dll
|       zstd-x64.dll
|       
\---resources
    |   7-zip.chm
    |   defaults.reg
    |   descript.ion
    |   history.7zip.txt
    |   info_without_codecs.txt
    |   info_with_codecs.txt
    |   license.7zip.txt
    |   license.zstd.txt
    |   readme.7zip.txt
    |   readme.zstd.md
    |   Uninstall.exe
    |   uninstall.reg
    |   
    \---Lang
            af.txt
            an.txt
            ar.txt
            ast.txt
            az.txt
            ba.txt
            be.txt
            bg.txt
            bn.txt
            br.txt
            ca.txt
            co.txt
            cs.txt
            cy.txt
            da.txt
            de.txt
            el.txt
            en.ttt
            eo.txt
            es.txt
            et.txt
            eu.txt
            ext.txt
            fa.txt
            fi.txt
            fr.txt
            fur.txt
            fy.txt
            ga.txt
            gl.txt
            gu.txt
            he.txt
            hi.txt
            hr.txt
            hu.txt
            hy.txt
            id.txt
            io.txt
            is.txt
            it.txt
            ja.txt
            ka.txt
            kaa.txt
            kab.txt
            kk.txt
            ko.txt
            ku-ckb.txt
            ku.txt
            ky.txt
            lij.txt
            lt.txt
            lv.txt
            mk.txt
            mn.txt
            mng.txt
            mng2.txt
            mr.txt
            ms.txt
            nb.txt
            ne.txt
            nl.txt
            nn.txt
            pa-in.txt
            pl.txt
            ps.txt
            pt-br.txt
            pt.txt
            ro.txt
            ru.txt
            sa.txt
            si.txt
            sk.txt
            sl.txt
            sq.txt
            sr-spc.txt
            sr-spl.txt
            sv.txt
            sw.txt
            ta.txt
            tg.txt
            th.txt
            tk.txt
            tr.txt
            tt.txt
            ug.txt
            uk.txt
            uz-cyrl.txt
            uz.txt
            va.txt
            vi.txt
            yo.txt
            zh-cn.txt
            zh-tw.txt
            
```

</details>
