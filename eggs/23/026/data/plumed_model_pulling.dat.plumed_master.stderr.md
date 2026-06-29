**Project ID:** [plumID:23.026]({{ '/' | absolute_url }}eggs/23/026/)  
Stderr for source:  plumed_model_pulling.dat   
Download: [zipped raw stdout](plumed_model_pulling.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_model_pulling.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[runnervmmklqx:05579] *** Process received signal ***
[runnervmmklqx:05579] Signal: Aborted (6)
[runnervmmklqx:05579] Signal code:  (-6)
[runnervmmklqx:05579] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7cd4845330]
[runnervmmklqx:05579] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7cd489eb2c]
[runnervmmklqx:05579] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7cd484527e]
[runnervmmklqx:05579] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7cd48288ff]
[runnervmmklqx:05579] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7cd4ca5ff5]
[runnervmmklqx:05579] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7cd4cbb0da]
[runnervmmklqx:05579] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7cd4ca5a55]
[runnervmmklqx:05579] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7cd4ca5a6f]
[runnervmmklqx:05579] [ 8] plumed_master(+0x146dd)[0x55c23c66c6dd]
[runnervmmklqx:05579] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7cd482a1ca]
[runnervmmklqx:05579] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7cd482a28b]
[runnervmmklqx:05579] [11] plumed_master(+0x15365)[0x55c23c66d365]
[runnervmmklqx:05579] *** End of error message ***
</pre>
{% endraw %}
