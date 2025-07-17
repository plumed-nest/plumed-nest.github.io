**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test14_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmq0rgcvqdmg:06326] *** Process received signal ***
[pkrvmq0rgcvqdmg:06326] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:06326] Signal code:  (-6)
[pkrvmq0rgcvqdmg:06326] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f10a3c45330]
[pkrvmq0rgcvqdmg:06326] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f10a3c9eb2c]
[pkrvmq0rgcvqdmg:06326] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f10a3c4527e]
[pkrvmq0rgcvqdmg:06326] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f10a3c288ff]
[pkrvmq0rgcvqdmg:06326] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f10a40a5ff5]
[pkrvmq0rgcvqdmg:06326] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f10a40bb0da]
[pkrvmq0rgcvqdmg:06326] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f10a40a5a55]
[pkrvmq0rgcvqdmg:06326] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f10a40a5a6f]
[pkrvmq0rgcvqdmg:06326] [ 8] plumed_master(+0x146dd)[0x55636fb0d6dd]
[pkrvmq0rgcvqdmg:06326] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f10a3c2a1ca]
[pkrvmq0rgcvqdmg:06326] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f10a3c2a28b]
[pkrvmq0rgcvqdmg:06326] [11] plumed_master(+0x15365)[0x55636fb0e365]
[pkrvmq0rgcvqdmg:06326] *** End of error message ***
</pre>
{% endraw %}
