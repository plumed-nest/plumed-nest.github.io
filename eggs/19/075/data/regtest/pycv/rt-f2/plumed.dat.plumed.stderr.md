**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-f2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONFUNCTION" is not known.
[runnervmgx7h7:09881] *** Process received signal ***
[runnervmgx7h7:09881] Signal: Aborted (6)
[runnervmgx7h7:09881] Signal code:  (-6)
[runnervmgx7h7:09881] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1a18645330]
[runnervmgx7h7:09881] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1a1869ec0c]
[runnervmgx7h7:09881] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1a1864527e]
[runnervmgx7h7:09881] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1a186288ff]
[runnervmgx7h7:09881] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1a18aa5ff5]
[runnervmgx7h7:09881] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1a18abb0da]
[runnervmgx7h7:09881] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1a18aa5a55]
[runnervmgx7h7:09881] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1a18aa5a6f]
[runnervmgx7h7:09881] [ 8] plumed(+0x146dd)[0x55696be3a6dd]
[runnervmgx7h7:09881] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1a1862a1ca]
[runnervmgx7h7:09881] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1a1862a28b]
[runnervmgx7h7:09881] [11] plumed(+0x15365)[0x55696be3b365]
[runnervmgx7h7:09881] *** End of error message ***
</pre>
{% endraw %}
