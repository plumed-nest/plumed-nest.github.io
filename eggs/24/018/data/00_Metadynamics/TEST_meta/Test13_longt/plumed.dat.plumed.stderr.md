**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test13_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmq0rgcvqdmg:06258] *** Process received signal ***
[pkrvmq0rgcvqdmg:06258] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:06258] Signal code:  (-6)
[pkrvmq0rgcvqdmg:06258] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f545e645330]
[pkrvmq0rgcvqdmg:06258] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f545e69eb2c]
[pkrvmq0rgcvqdmg:06258] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f545e64527e]
[pkrvmq0rgcvqdmg:06258] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f545e6288ff]
[pkrvmq0rgcvqdmg:06258] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f545eaa5ff5]
[pkrvmq0rgcvqdmg:06258] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f545eabb0da]
[pkrvmq0rgcvqdmg:06258] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f545eaa5a55]
[pkrvmq0rgcvqdmg:06258] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f545eaa5a6f]
[pkrvmq0rgcvqdmg:06258] [ 8] plumed(+0x146dd)[0x56140aae96dd]
[pkrvmq0rgcvqdmg:06258] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f545e62a1ca]
[pkrvmq0rgcvqdmg:06258] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f545e62a28b]
[pkrvmq0rgcvqdmg:06258] [11] plumed(+0x15365)[0x56140aaea365]
[pkrvmq0rgcvqdmg:06258] *** End of error message ***
</pre>
{% endraw %}
