**Project ID:** [plumID:21.044]({{ '/' | absolute_url }}eggs/21/044/)  
Stderr for source:  driver.dat   
Download: [zipped raw stdout](driver.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](driver.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'std::out_of_range'
what():  map::at
[pkrvm7jw40e0xgp:09085] *** Process received signal ***
[pkrvm7jw40e0xgp:09085] Signal: Aborted (6)
[pkrvm7jw40e0xgp:09085] Signal code:  (-6)
[pkrvm7jw40e0xgp:09085] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8d73245330]
[pkrvm7jw40e0xgp:09085] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8d7329eb2c]
[pkrvm7jw40e0xgp:09085] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8d7324527e]
[pkrvm7jw40e0xgp:09085] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8d732288ff]
[pkrvm7jw40e0xgp:09085] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8d736a5ff5]
[pkrvm7jw40e0xgp:09085] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8d736bb0da]
[pkrvm7jw40e0xgp:09085] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8d736a5a55]
[pkrvm7jw40e0xgp:09085] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8d736a5a6f]
[pkrvm7jw40e0xgp:09085] [ 8] plumed_master(+0x146dd)[0x55e3fd3f06dd]
[pkrvm7jw40e0xgp:09085] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8d7322a1ca]
[pkrvm7jw40e0xgp:09085] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8d7322a28b]
[pkrvm7jw40e0xgp:09085] [11] plumed_master(+0x15365)[0x55e3fd3f1365]
[pkrvm7jw40e0xgp:09085] *** End of error message ***
</pre>
{% endraw %}
