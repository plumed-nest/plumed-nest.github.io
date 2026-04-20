**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w27-s6.924/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmeorf1:11317] *** Process received signal ***
[runnervmeorf1:11317] Signal: Aborted (6)
[runnervmeorf1:11317] Signal code:  (-6)
[runnervmeorf1:11317] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f23ce645330]
[runnervmeorf1:11317] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f23ce69eb2c]
[runnervmeorf1:11317] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f23ce64527e]
[runnervmeorf1:11317] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f23ce6288ff]
[runnervmeorf1:11317] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f23ceaa5ff5]
[runnervmeorf1:11317] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f23ceabb0da]
[runnervmeorf1:11317] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f23ceaa5a55]
[runnervmeorf1:11317] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f23ceaa5a6f]
[runnervmeorf1:11317] [ 8] plumed_master(+0x146dd)[0x5603df7b86dd]
[runnervmeorf1:11317] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f23ce62a1ca]
[runnervmeorf1:11317] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f23ce62a28b]
[runnervmeorf1:11317] [11] plumed_master(+0x15365)[0x5603df7b9365]
[runnervmeorf1:11317] *** End of error message ***
</pre>
{% endraw %}
