**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w15-s4.332/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmgx7h7:09217] *** Process received signal ***
[runnervmgx7h7:09217] Signal: Aborted (6)
[runnervmgx7h7:09217] Signal code:  (-6)
[runnervmgx7h7:09217] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f380be45330]
[runnervmgx7h7:09217] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f380be9ec0c]
[runnervmgx7h7:09217] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f380be4527e]
[runnervmgx7h7:09217] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f380be288ff]
[runnervmgx7h7:09217] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f380c2a5ff5]
[runnervmgx7h7:09217] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f380c2bb0da]
[runnervmgx7h7:09217] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f380c2a5a55]
[runnervmgx7h7:09217] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f380c2a5a6f]
[runnervmgx7h7:09217] [ 8] plumed(+0x146dd)[0x5648dbd706dd]
[runnervmgx7h7:09217] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f380be2a1ca]
[runnervmgx7h7:09217] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f380be2a28b]
[runnervmgx7h7:09217] [11] plumed(+0x15365)[0x5648dbd71365]
[runnervmgx7h7:09217] *** End of error message ***
</pre>
{% endraw %}
