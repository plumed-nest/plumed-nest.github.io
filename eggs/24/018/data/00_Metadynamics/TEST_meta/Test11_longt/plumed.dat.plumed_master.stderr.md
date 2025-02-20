**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test11_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1444-322:05742] *** Process received signal ***
[fv-az1444-322:05742] Signal: Aborted (6)
[fv-az1444-322:05742] Signal code:  (-6)
[fv-az1444-322:05742] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f05ac045330]
[fv-az1444-322:05742] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f05ac09eb2c]
[fv-az1444-322:05742] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f05ac04527e]
[fv-az1444-322:05742] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f05ac0288ff]
[fv-az1444-322:05742] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f05ac4a5ff5]
[fv-az1444-322:05742] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f05ac4bb0da]
[fv-az1444-322:05742] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f05ac4a5a55]
[fv-az1444-322:05742] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f05ac4a5a6f]
[fv-az1444-322:05742] [ 8] plumed_master(+0x146dd)[0x55c78b0456dd]
[fv-az1444-322:05742] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f05ac02a1ca]
[fv-az1444-322:05742] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f05ac02a28b]
[fv-az1444-322:05742] [11] plumed_master(+0x15365)[0x55c78b046365]
[fv-az1444-322:05742] *** End of error message ***
</pre>
{% endraw %}
