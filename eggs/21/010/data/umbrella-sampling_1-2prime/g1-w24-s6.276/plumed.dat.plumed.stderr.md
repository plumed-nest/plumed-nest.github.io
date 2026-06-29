**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w24-s6.276/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmmklqx:11310] *** Process received signal ***
[runnervmmklqx:11310] Signal: Aborted (6)
[runnervmmklqx:11310] Signal code:  (-6)
[runnervmmklqx:11310] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff8e6645330]
[runnervmmklqx:11310] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff8e669eb2c]
[runnervmmklqx:11310] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff8e664527e]
[runnervmmklqx:11310] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff8e66288ff]
[runnervmmklqx:11310] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff8e6aa5ff5]
[runnervmmklqx:11310] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff8e6abb0da]
[runnervmmklqx:11310] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff8e6aa5a55]
[runnervmmklqx:11310] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff8e6aa5a6f]
[runnervmmklqx:11310] [ 8] plumed(+0x146dd)[0x55b4388f46dd]
[runnervmmklqx:11310] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff8e662a1ca]
[runnervmmklqx:11310] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff8e662a28b]
[runnervmmklqx:11310] [11] plumed(+0x15365)[0x55b4388f5365]
[runnervmmklqx:11310] *** End of error message ***
</pre>
{% endraw %}
