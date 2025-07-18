# adm_training_task4
<h1 align="center">Занятие 4. Практические навыки работы с ZFS</h1>
<h3 class="western"><a name="_heading=h.h6i87lkp3f19"></a> <span style="font-family: Roboto, serif;"><span style="font-size: small;">Описание домашнего задания</span></span></h3>
<ol>
<li style="font-weight: 400;"><span style="font-weight: 400;">Определить алгоритм с наилучшим сжатием:</span></li>
<ul>
<li style="font-weight: 400;"><span style="font-weight: 400;">Определить какие алгоритмы сжатия поддерживает zfs (gzip, zle, lzjb, lz4);</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">создать 4 файловых системы на каждой применить свой алгоритм сжатия;</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">для сжатия использовать либо текстовый файл, либо группу файлов.</span></li>
</ul>
<li style="font-weight: 400;"><span style="font-weight: 400;">Определить настройки пула.</span></li>
<ul>
<li style="font-weight: 400;"><span style="font-weight: 400;">С помощью команды zfs import собрать pool ZFS.</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">Командами zfs определить настройки:</span></li>
<p><span style="font-weight: 400;">&nbsp;&nbsp;&nbsp;&nbsp;- размер хранилища;</span></p>
<p><span style="font-weight: 400;">&nbsp;&nbsp;&nbsp;&nbsp;- тип pool;</span></p>
<p><span style="font-weight: 400;">&nbsp;&nbsp;&nbsp;&nbsp;- значение recordsize;</span></p>
<p><span style="font-weight: 400;">&nbsp;&nbsp;&nbsp;&nbsp;- какое сжатие используется;</span></p>
<p><span style="font-weight: 400;">&nbsp;&nbsp;&nbsp;&nbsp;- какая контрольная сумма используется.</span></p>
</ul>
<li style="font-weight: 400;"><span style="font-weight: 400;">Работа со снапшотами:</span></li>
<ul>
<li style="font-weight: 400;"><span style="font-weight: 400;">скопировать файл из удаленной директории;</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">восстановить файл локально. zfs receive;</span></li>
<li style="font-weight: 400;"><span style="font-weight: 400;">найти зашифрованное сообщение в файле secret_message.</span></li>
</ul>
</ol>
<p style="line-height: 100%; margin-bottom: 0cm;">&nbsp;</p>
<h3 class="western"><a name="_heading=h.df570rpzx1qg"></a><span style="font-family: Roboto, serif;"><span style="font-size: small;">Используемые ОС</span></span></h3>
<p style="line-height: 108%; margin-bottom: 0.28cm;" align="justify"><span style="font-family: Roboto, serif;">Хостовая ОС: Ubuntu 24.04 Desktop, гостевая система Ubuntu 24.04 Desktop.&nbsp;<span style="font-family: Roboto, serif;">VirtualBox версия 7.0.16_Ubuntu r162802</span></span></p>
<p style="line-height: 108%; margin-bottom: 0.28cm;" align="justify">&nbsp;</p>
<h3 class="western"><span style="font-family: Roboto, serif;"><span style="font-size: small;">Выполнение</span></span></h3>
