**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-f1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONFUNCTION" is not known.
[runnervmmklqx:10350] *** Process received signal ***
[runnervmmklqx:10350] Signal: Aborted (6)
[runnervmmklqx:10350] Signal code:  (-6)
[runnervmmklqx:10350] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd4f1845330]
[runnervmmklqx:10350] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd4f189eb2c]
[runnervmmklqx:10350] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd4f184527e]
[runnervmmklqx:10350] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd4f18288ff]
[runnervmmklqx:10350] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd4f1ca5ff5]
[runnervmmklqx:10350] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd4f1cbb0da]
[runnervmmklqx:10350] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd4f1ca5a55]
[runnervmmklqx:10350] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd4f1ca5a6f]
[runnervmmklqx:10350] [ 8] plumed_master(+0x146dd)[0x55983c1ad6dd]
[runnervmmklqx:10350] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd4f182a1ca]
[runnervmmklqx:10350] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd4f182a28b]
[runnervmmklqx:10350] [11] plumed_master(+0x15365)[0x55983c1ae365]
[runnervmmklqx:10350] *** End of error message ***
</pre>
{% endraw %}
