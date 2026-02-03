**Project ID:** [plumID:21.044]({{ '/' | absolute_url }}eggs/21/044/)  
Stderr for source:  driver.dat   
Download: [zipped raw stdout](driver.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](driver.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'std::out_of_range'
what():  map::at
[runnervmkj6or:07319] *** Process received signal ***
[runnervmkj6or:07319] Signal: Aborted (6)
[runnervmkj6or:07319] Signal code:  (-6)
[runnervmkj6or:07319] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3790245330]
[runnervmkj6or:07319] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f379029eb2c]
[runnervmkj6or:07319] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f379024527e]
[runnervmkj6or:07319] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f37902288ff]
[runnervmkj6or:07319] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f37906a5ff5]
[runnervmkj6or:07319] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f37906bb0da]
[runnervmkj6or:07319] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f37906a5a55]
[runnervmkj6or:07319] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f37906a5a6f]
[runnervmkj6or:07319] [ 8] plumed_master(+0x146dd)[0x5562d0f6d6dd]
[runnervmkj6or:07319] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f379022a1ca]
[runnervmkj6or:07319] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f379022a28b]
[runnervmkj6or:07319] [11] plumed_master(+0x15365)[0x5562d0f6e365]
[runnervmkj6or:07319] *** End of error message ***
</pre>
{% endraw %}
