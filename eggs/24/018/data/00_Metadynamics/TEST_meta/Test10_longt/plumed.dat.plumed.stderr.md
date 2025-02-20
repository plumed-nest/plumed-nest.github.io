**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test10_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1444-322:05668] *** Process received signal ***
[fv-az1444-322:05668] Signal: Aborted (6)
[fv-az1444-322:05668] Signal code:  (-6)
[fv-az1444-322:05668] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7a1b445330]
[fv-az1444-322:05668] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7a1b49eb2c]
[fv-az1444-322:05668] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7a1b44527e]
[fv-az1444-322:05668] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7a1b4288ff]
[fv-az1444-322:05668] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7a1b8a5ff5]
[fv-az1444-322:05668] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7a1b8bb0da]
[fv-az1444-322:05668] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7a1b8a5a55]
[fv-az1444-322:05668] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7a1b8a5a6f]
[fv-az1444-322:05668] [ 8] plumed(+0x146dd)[0x55c4eb8a96dd]
[fv-az1444-322:05668] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7a1b42a1ca]
[fv-az1444-322:05668] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7a1b42a28b]
[fv-az1444-322:05668] [11] plumed(+0x15365)[0x55c4eb8aa365]
[fv-az1444-322:05668] *** End of error message ***
</pre>
{% endraw %}
