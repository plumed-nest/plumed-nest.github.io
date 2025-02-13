**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test10_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1280-696:05448] *** Process received signal ***
[fv-az1280-696:05448] Signal: Aborted (6)
[fv-az1280-696:05448] Signal code:  (-6)
[fv-az1280-696:05448] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ffb43245330]
[fv-az1280-696:05448] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ffb4329eb2c]
[fv-az1280-696:05448] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ffb4324527e]
[fv-az1280-696:05448] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ffb432288ff]
[fv-az1280-696:05448] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ffb436a5ff5]
[fv-az1280-696:05448] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ffb436bb0da]
[fv-az1280-696:05448] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ffb436a5a55]
[fv-az1280-696:05448] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ffb436a5a6f]
[fv-az1280-696:05448] [ 8] plumed_master(+0x146dd)[0x560110ea66dd]
[fv-az1280-696:05448] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ffb4322a1ca]
[fv-az1280-696:05448] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ffb4322a28b]
[fv-az1280-696:05448] [11] plumed_master(+0x15365)[0x560110ea7365]
[fv-az1280-696:05448] *** End of error message ***
</pre>
{% endraw %}
