**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w14-s4.116/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmeorf1:10546] *** Process received signal ***
[runnervmeorf1:10546] Signal: Aborted (6)
[runnervmeorf1:10546] Signal code:  (-6)
[runnervmeorf1:10546] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f57dd845330]
[runnervmeorf1:10546] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f57dd89eb2c]
[runnervmeorf1:10546] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f57dd84527e]
[runnervmeorf1:10546] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f57dd8288ff]
[runnervmeorf1:10546] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f57ddca5ff5]
[runnervmeorf1:10546] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f57ddcbb0da]
[runnervmeorf1:10546] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f57ddca5a55]
[runnervmeorf1:10546] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f57ddca5a6f]
[runnervmeorf1:10546] [ 8] plumed(+0x146dd)[0x564ce60f96dd]
[runnervmeorf1:10546] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f57dd82a1ca]
[runnervmeorf1:10546] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f57dd82a28b]
[runnervmeorf1:10546] [11] plumed(+0x15365)[0x564ce60fa365]
[runnervmeorf1:10546] *** End of error message ***
</pre>
{% endraw %}
