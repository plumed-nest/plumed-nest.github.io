**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[runnervmgx7h7:09728] *** Process received signal ***
[runnervmgx7h7:09728] Signal: Aborted (6)
[runnervmgx7h7:09728] Signal code:  (-6)
[runnervmgx7h7:09728] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f666fa45330]
[runnervmgx7h7:09728] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f666fa9ec0c]
[runnervmgx7h7:09728] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f666fa4527e]
[runnervmgx7h7:09728] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f666fa288ff]
[runnervmgx7h7:09728] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f666fea5ff5]
[runnervmgx7h7:09728] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f666febb0da]
[runnervmgx7h7:09728] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f666fea5a55]
[runnervmgx7h7:09728] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f666fea5a6f]
[runnervmgx7h7:09728] [ 8] plumed(+0x146dd)[0x5601376286dd]
[runnervmgx7h7:09728] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f666fa2a1ca]
[runnervmgx7h7:09728] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f666fa2a28b]
[runnervmgx7h7:09728] [11] plumed(+0x15365)[0x560137629365]
[runnervmgx7h7:09728] *** End of error message ***
</pre>
{% endraw %}
