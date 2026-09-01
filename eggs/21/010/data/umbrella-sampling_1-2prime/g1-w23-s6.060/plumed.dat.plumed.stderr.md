**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w23-s6.060/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmgx7h7:09678] *** Process received signal ***
[runnervmgx7h7:09678] Signal: Aborted (6)
[runnervmgx7h7:09678] Signal code:  (-6)
[runnervmgx7h7:09678] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f775f045330]
[runnervmgx7h7:09678] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f775f09ec0c]
[runnervmgx7h7:09678] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f775f04527e]
[runnervmgx7h7:09678] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f775f0288ff]
[runnervmgx7h7:09678] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f775f4a5ff5]
[runnervmgx7h7:09678] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f775f4bb0da]
[runnervmgx7h7:09678] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f775f4a5a55]
[runnervmgx7h7:09678] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f775f4a5a6f]
[runnervmgx7h7:09678] [ 8] plumed(+0x146dd)[0x55e4a00566dd]
[runnervmgx7h7:09678] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f775f02a1ca]
[runnervmgx7h7:09678] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f775f02a28b]
[runnervmgx7h7:09678] [11] plumed(+0x15365)[0x55e4a0057365]
[runnervmgx7h7:09678] *** End of error message ***
</pre>
{% endraw %}
