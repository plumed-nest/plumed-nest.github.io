**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test13_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmq0rgcvqdmg:06274] *** Process received signal ***
[pkrvmq0rgcvqdmg:06274] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:06274] Signal code:  (-6)
[pkrvmq0rgcvqdmg:06274] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5d94245330]
[pkrvmq0rgcvqdmg:06274] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5d9429eb2c]
[pkrvmq0rgcvqdmg:06274] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5d9424527e]
[pkrvmq0rgcvqdmg:06274] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5d942288ff]
[pkrvmq0rgcvqdmg:06274] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5d946a5ff5]
[pkrvmq0rgcvqdmg:06274] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5d946bb0da]
[pkrvmq0rgcvqdmg:06274] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5d946a5a55]
[pkrvmq0rgcvqdmg:06274] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5d946a5a6f]
[pkrvmq0rgcvqdmg:06274] [ 8] plumed_master(+0x146dd)[0x5587202556dd]
[pkrvmq0rgcvqdmg:06274] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5d9422a1ca]
[pkrvmq0rgcvqdmg:06274] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5d9422a28b]
[pkrvmq0rgcvqdmg:06274] [11] plumed_master(+0x15365)[0x558720256365]
[pkrvmq0rgcvqdmg:06274] *** End of error message ***
</pre>
{% endraw %}
