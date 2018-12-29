
Django2.1 Tutotrial Note
====================

這網站

https://2019-django21-tutotrial-note.readthedocs.io/en/latest/index.html


我練習官網教程幾十次，並不是逐字看的，總是抓著能做的先做，有問題時回來找解簽，每次或多或少都有些心得，也曾經有些誤解。
總而言之，實戰很重要，觀念也很重，知行要合一。

有這個機會理解了 Read The Doc

https://readthedocs.org/

同時也找到 Django 目前最新版本的文檔的代碼

https://github.com/django/django

經過實驗，可以以最小的更改原 .txt 為 .rst 即可使用。

這樣子，就可以把我的心得筆記直接放在文件裡。


Note 的寫法

.. note::
   This is note text. Use a note for information you want the user to
   pay particular attention to.

   If note text runs over a line, make sure the lines wrap and are indented to
   the same level as the note tag. If formatting is incorrect, part of the note
   might not render in the HTML output.

   Notes can have more than one paragraph. Successive paragraphs must
   indent to the same level as the rest of the note.
   


Warning 的寫法

.. warning::
    This is warning text. Use a warning for information the user must
    understand to avoid negative consequences.

    Warnings are formatted in the same way as notes. In the same way,
    lines must be broken and indented under the warning tag.


現在，2018-12-28，發現生成的PDF沒有上述 Note Warning 的效果，在實驗 cs50 的工具是否可以實現。

https://cs50.readthedocs.io/render50/


* To know which Python you're using, it applies to virtual venv as well

    $ which python







Table of Contents
-----------------

.. toctree::
   intro/tutorial01
   intro/tutorial02
   intro/tutorial03
   intro/tutorial04
   intro/tutorial05
   intro/tutorial06
   intro/tutorial07
   
