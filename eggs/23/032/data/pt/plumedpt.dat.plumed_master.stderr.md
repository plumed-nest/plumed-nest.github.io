**Project ID:** [plumID:23.032]({{ '/' | absolute_url }}eggs/23/032/)  
Stderr for source:  pt/plumedpt.dat   
Download: [zipped raw stdout](plumedpt.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumedpt.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTORCH_MODEL_CV" is not known.
[runnervmmklqx:05322] *** Process received signal ***
[runnervmmklqx:05322] Signal: Aborted (6)
[runnervmmklqx:05322] Signal code:  (-6)
[runnervmmklqx:05322] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd130c45330]
[runnervmmklqx:05322] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd130c9eb2c]
[runnervmmklqx:05322] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd130c4527e]
[runnervmmklqx:05322] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd130c288ff]
[runnervmmklqx:05322] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd1310a5ff5]
[runnervmmklqx:05322] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd1310bb0da]
[runnervmmklqx:05322] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd1310a5a55]
[runnervmmklqx:05322] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd1310a5a6f]
[runnervmmklqx:05322] [ 8] plumed_master(+0x146dd)[0x561562a246dd]
[runnervmmklqx:05322] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd130c2a1ca]
[runnervmmklqx:05322] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd130c2a28b]
[runnervmmklqx:05322] [11] plumed_master(+0x15365)[0x561562a25365]
[runnervmmklqx:05322] *** End of error message ***
</pre>
{% endraw %}
