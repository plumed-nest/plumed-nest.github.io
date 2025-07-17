**Project ID:** [plumID:23.043]({{ '/' | absolute_url }}eggs/23/043/)  
Stderr for source:  metad-example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "SPHERICAL_EXPANSION" is not known.
[pkrvmq0rgcvqdmg:08138] *** Process received signal ***
[pkrvmq0rgcvqdmg:08138] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:08138] Signal code:  (-6)
[pkrvmq0rgcvqdmg:08138] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff744645330]
[pkrvmq0rgcvqdmg:08138] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff74469eb2c]
[pkrvmq0rgcvqdmg:08138] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff74464527e]
[pkrvmq0rgcvqdmg:08138] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff7446288ff]
[pkrvmq0rgcvqdmg:08138] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff744aa5ff5]
[pkrvmq0rgcvqdmg:08138] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff744abb0da]
[pkrvmq0rgcvqdmg:08138] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff744aa5a55]
[pkrvmq0rgcvqdmg:08138] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff744aa5a6f]
[pkrvmq0rgcvqdmg:08138] [ 8] plumed_master(+0x146dd)[0x5641dac0d6dd]
[pkrvmq0rgcvqdmg:08138] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff74462a1ca]
[pkrvmq0rgcvqdmg:08138] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff74462a28b]
[pkrvmq0rgcvqdmg:08138] [11] plumed_master(+0x15365)[0x5641dac0e365]
[pkrvmq0rgcvqdmg:08138] *** End of error message ***
</pre>
{% endraw %}
