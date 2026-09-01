**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-multi-1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[runnervmgx7h7:10089] *** Process received signal ***
[runnervmgx7h7:10089] Signal: Aborted (6)
[runnervmgx7h7:10089] Signal code:  (-6)
[runnervmgx7h7:10089] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f438c045330]
[runnervmgx7h7:10089] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f438c09ec0c]
[runnervmgx7h7:10089] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f438c04527e]
[runnervmgx7h7:10089] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f438c0288ff]
[runnervmgx7h7:10089] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f438c4a5ff5]
[runnervmgx7h7:10089] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f438c4bb0da]
[runnervmgx7h7:10089] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f438c4a5a55]
[runnervmgx7h7:10089] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f438c4a5a6f]
[runnervmgx7h7:10089] [ 8] plumed(+0x146dd)[0x55e8aebac6dd]
[runnervmgx7h7:10089] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f438c02a1ca]
[runnervmgx7h7:10089] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f438c02a28b]
[runnervmgx7h7:10089] [11] plumed(+0x15365)[0x55e8aebad365]
[runnervmgx7h7:10089] *** End of error message ***
</pre>
{% endraw %}
