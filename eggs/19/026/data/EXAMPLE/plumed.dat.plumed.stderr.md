**Project ID:** [plumID:19.026]({{ '/' | absolute_url }}eggs/19/026/)  
Stderr for source:  EXAMPLE/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HBOND_COORD" is not known.
[runnervmkj6or:08541] *** Process received signal ***
[runnervmkj6or:08541] Signal: Aborted (6)
[runnervmkj6or:08541] Signal code:  (-6)
[runnervmkj6or:08541] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7fc9045330]
[runnervmkj6or:08541] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7fc909eb2c]
[runnervmkj6or:08541] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7fc904527e]
[runnervmkj6or:08541] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7fc90288ff]
[runnervmkj6or:08541] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7fc94a5ff5]
[runnervmkj6or:08541] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7fc94bb0da]
[runnervmkj6or:08541] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7fc94a5a55]
[runnervmkj6or:08541] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7fc94a5a6f]
[runnervmkj6or:08541] [ 8] plumed(+0x146dd)[0x5646d8f196dd]
[runnervmkj6or:08541] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7fc902a1ca]
[runnervmkj6or:08541] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7fc902a28b]
[runnervmkj6or:08541] [11] plumed(+0x15365)[0x5646d8f1a365]
[runnervmkj6or:08541] *** End of error message ***
</pre>
{% endraw %}
