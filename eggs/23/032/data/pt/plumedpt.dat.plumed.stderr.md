**Project ID:** [plumID:23.032]({{ '/' | absolute_url }}eggs/23/032/)  
Stderr for source:  pt/plumedpt.dat   
Download: [zipped raw stdout](plumedpt.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumedpt.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTORCH_MODEL_CV" is not known.
[runnervmkj6or:05418] *** Process received signal ***
[runnervmkj6or:05418] Signal: Aborted (6)
[runnervmkj6or:05418] Signal code:  (-6)
[runnervmkj6or:05418] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7e6f045330]
[runnervmkj6or:05418] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7e6f09eb2c]
[runnervmkj6or:05418] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7e6f04527e]
[runnervmkj6or:05418] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7e6f0288ff]
[runnervmkj6or:05418] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7e6f4a5ff5]
[runnervmkj6or:05418] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7e6f4bb0da]
[runnervmkj6or:05418] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7e6f4a5a55]
[runnervmkj6or:05418] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7e6f4a5a6f]
[runnervmkj6or:05418] [ 8] plumed(+0x146dd)[0x55ce5e9ae6dd]
[runnervmkj6or:05418] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7e6f02a1ca]
[runnervmkj6or:05418] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7e6f02a28b]
[runnervmkj6or:05418] [11] plumed(+0x15365)[0x55ce5e9af365]
[runnervmkj6or:05418] *** End of error message ***
</pre>
{% endraw %}
