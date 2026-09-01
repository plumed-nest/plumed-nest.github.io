**Project ID:** [plumID:19.026]({{ '/' | absolute_url }}eggs/19/026/)  
Stderr for source:  EXAMPLE/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HBOND_COORD" is not known.
[runnervmgx7h7:11247] *** Process received signal ***
[runnervmgx7h7:11247] Signal: Aborted (6)
[runnervmgx7h7:11247] Signal code:  (-6)
[runnervmgx7h7:11247] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fec50845330]
[runnervmgx7h7:11247] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fec5089ec0c]
[runnervmgx7h7:11247] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fec5084527e]
[runnervmgx7h7:11247] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fec508288ff]
[runnervmgx7h7:11247] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fec50ca5ff5]
[runnervmgx7h7:11247] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fec50cbb0da]
[runnervmgx7h7:11247] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fec50ca5a55]
[runnervmgx7h7:11247] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fec50ca5a6f]
[runnervmgx7h7:11247] [ 8] plumed(+0x146dd)[0x55c2179c66dd]
[runnervmgx7h7:11247] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fec5082a1ca]
[runnervmgx7h7:11247] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fec5082a28b]
[runnervmgx7h7:11247] [11] plumed(+0x15365)[0x55c2179c7365]
[runnervmgx7h7:11247] *** End of error message ***
</pre>
{% endraw %}
