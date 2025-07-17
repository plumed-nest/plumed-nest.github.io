**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test15_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmq0rgcvqdmg:06361] *** Process received signal ***
[pkrvmq0rgcvqdmg:06361] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:06361] Signal code:  (-6)
[pkrvmq0rgcvqdmg:06361] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd2a9645330]
[pkrvmq0rgcvqdmg:06361] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd2a969eb2c]
[pkrvmq0rgcvqdmg:06361] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd2a964527e]
[pkrvmq0rgcvqdmg:06361] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd2a96288ff]
[pkrvmq0rgcvqdmg:06361] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd2a9aa5ff5]
[pkrvmq0rgcvqdmg:06361] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd2a9abb0da]
[pkrvmq0rgcvqdmg:06361] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd2a9aa5a55]
[pkrvmq0rgcvqdmg:06361] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd2a9aa5a6f]
[pkrvmq0rgcvqdmg:06361] [ 8] plumed(+0x146dd)[0x556a1cb576dd]
[pkrvmq0rgcvqdmg:06361] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd2a962a1ca]
[pkrvmq0rgcvqdmg:06361] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd2a962a28b]
[pkrvmq0rgcvqdmg:06361] [11] plumed(+0x15365)[0x556a1cb58365]
[pkrvmq0rgcvqdmg:06361] *** End of error message ***
</pre>
{% endraw %}
