**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w19-s5.196/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmmklqx:11003] *** Process received signal ***
[runnervmmklqx:11003] Signal: Aborted (6)
[runnervmmklqx:11003] Signal code:  (-6)
[runnervmmklqx:11003] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc551845330]
[runnervmmklqx:11003] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc55189eb2c]
[runnervmmklqx:11003] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc55184527e]
[runnervmmklqx:11003] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc5518288ff]
[runnervmmklqx:11003] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc551ca5ff5]
[runnervmmklqx:11003] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc551cbb0da]
[runnervmmklqx:11003] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc551ca5a55]
[runnervmmklqx:11003] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc551ca5a6f]
[runnervmmklqx:11003] [ 8] plumed(+0x146dd)[0x55c56c38a6dd]
[runnervmmklqx:11003] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc55182a1ca]
[runnervmmklqx:11003] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc55182a28b]
[runnervmmklqx:11003] [11] plumed(+0x15365)[0x55c56c38b365]
[runnervmmklqx:11003] *** End of error message ***
</pre>
{% endraw %}
