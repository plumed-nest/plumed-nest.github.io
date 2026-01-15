**Project ID:** [plumID:21.044]({{ '/' | absolute_url }}eggs/21/044/)  
Stderr for source:  driver.dat   
Download: [zipped raw stdout](driver.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](driver.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'std::out_of_range'
what():  map::at
[runnervmi13qx:35723] *** Process received signal ***
[runnervmi13qx:35723] Signal: Aborted (6)
[runnervmi13qx:35723] Signal code:  (-6)
[runnervmi13qx:35723] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc9cb045330]
[runnervmi13qx:35723] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc9cb09eb2c]
[runnervmi13qx:35723] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc9cb04527e]
[runnervmi13qx:35723] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc9cb0288ff]
[runnervmi13qx:35723] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc9cb4a5ff5]
[runnervmi13qx:35723] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc9cb4bb0da]
[runnervmi13qx:35723] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc9cb4a5a55]
[runnervmi13qx:35723] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc9cb4a5a6f]
[runnervmi13qx:35723] [ 8] plumed_master(+0x146dd)[0x558f98c0a6dd]
[runnervmi13qx:35723] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc9cb02a1ca]
[runnervmi13qx:35723] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc9cb02a28b]
[runnervmi13qx:35723] [11] plumed_master(+0x15365)[0x558f98c0b365]
[runnervmi13qx:35723] *** End of error message ***
</pre>
{% endraw %}
