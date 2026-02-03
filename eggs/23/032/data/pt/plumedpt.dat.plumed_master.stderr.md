**Project ID:** [plumID:23.032]({{ '/' | absolute_url }}eggs/23/032/)  
Stderr for source:  pt/plumedpt.dat   
Download: [zipped raw stdout](plumedpt.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumedpt.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTORCH_MODEL_CV" is not known.
[runnervmkj6or:05433] *** Process received signal ***
[runnervmkj6or:05433] Signal: Aborted (6)
[runnervmkj6or:05433] Signal code:  (-6)
[runnervmkj6or:05433] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa9ed045330]
[runnervmkj6or:05433] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa9ed09eb2c]
[runnervmkj6or:05433] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa9ed04527e]
[runnervmkj6or:05433] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa9ed0288ff]
[runnervmkj6or:05433] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa9ed4a5ff5]
[runnervmkj6or:05433] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa9ed4bb0da]
[runnervmkj6or:05433] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa9ed4a5a55]
[runnervmkj6or:05433] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa9ed4a5a6f]
[runnervmkj6or:05433] [ 8] plumed_master(+0x146dd)[0x55799a9456dd]
[runnervmkj6or:05433] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa9ed02a1ca]
[runnervmkj6or:05433] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa9ed02a28b]
[runnervmkj6or:05433] [11] plumed_master(+0x15365)[0x55799a946365]
[runnervmkj6or:05433] *** End of error message ***
</pre>
{% endraw %}
