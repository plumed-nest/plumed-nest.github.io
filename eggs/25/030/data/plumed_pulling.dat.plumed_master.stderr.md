**Project ID:** [plumID:25.030]({{ '/' | absolute_url }}eggs/25/030/)  
Stderr for source:  plumed_pulling.dat   
Download: [zipped raw stdout](plumed_pulling.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_pulling.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[runnervmeorf1:04233] *** Process received signal ***
[runnervmeorf1:04233] Signal: Aborted (6)
[runnervmeorf1:04233] Signal code:  (-6)
[runnervmeorf1:04233] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa352645330]
[runnervmeorf1:04233] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa35269eb2c]
[runnervmeorf1:04233] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa35264527e]
[runnervmeorf1:04233] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa3526288ff]
[runnervmeorf1:04233] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa352aa5ff5]
[runnervmeorf1:04233] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa352abb0da]
[runnervmeorf1:04233] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa352aa5a55]
[runnervmeorf1:04233] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa352aa5a6f]
[runnervmeorf1:04233] [ 8] plumed_master(+0x146dd)[0x564414ce46dd]
[runnervmeorf1:04233] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa35262a1ca]
[runnervmeorf1:04233] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa35262a28b]
[runnervmeorf1:04233] [11] plumed_master(+0x15365)[0x564414ce5365]
[runnervmeorf1:04233] *** End of error message ***
</pre>
{% endraw %}
