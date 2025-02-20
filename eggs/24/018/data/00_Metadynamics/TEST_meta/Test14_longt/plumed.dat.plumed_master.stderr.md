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
[fv-az1444-322:05901] *** Process received signal ***
[fv-az1444-322:05901] Signal: Aborted (6)
[fv-az1444-322:05901] Signal code:  (-6)
[fv-az1444-322:05901] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff112045330]
[fv-az1444-322:05901] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff11209eb2c]
[fv-az1444-322:05901] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff11204527e]
[fv-az1444-322:05901] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff1120288ff]
[fv-az1444-322:05901] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff1124a5ff5]
[fv-az1444-322:05901] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff1124bb0da]
[fv-az1444-322:05901] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff1124a5a55]
[fv-az1444-322:05901] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff1124a5a6f]
[fv-az1444-322:05901] [ 8] plumed_master(+0x146dd)[0x56430e2e86dd]
[fv-az1444-322:05901] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff11202a1ca]
[fv-az1444-322:05901] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff11202a28b]
[fv-az1444-322:05901] [11] plumed_master(+0x15365)[0x56430e2e9365]
[fv-az1444-322:05901] *** End of error message ***
</pre>
{% endraw %}
