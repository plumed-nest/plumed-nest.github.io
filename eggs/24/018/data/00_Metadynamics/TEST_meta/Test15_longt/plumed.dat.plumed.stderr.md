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
[fv-az1442-469:04035] *** Process received signal ***
[fv-az1442-469:04035] Signal: Aborted (6)
[fv-az1442-469:04035] Signal code:  (-6)
[fv-az1442-469:04035] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f46ae642520]
[fv-az1442-469:04035] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f46ae6969fc]
[fv-az1442-469:04035] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f46ae642476]
[fv-az1442-469:04035] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f46ae6287f3]
[fv-az1442-469:04035] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f46aeaa2b9e]
[fv-az1442-469:04035] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f46aeaae20c]
[fv-az1442-469:04035] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f46aeaae277]
[fv-az1442-469:04035] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f46aeaae52b]
[fv-az1442-469:04035] [ 8] plumed(+0x14254)[0x55ca05ba5254]
[fv-az1442-469:04035] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f46ae629d90]
[fv-az1442-469:04035] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f46ae629e40]
[fv-az1442-469:04035] [11] plumed(+0x14eb5)[0x55ca05ba5eb5]
[fv-az1442-469:04035] *** End of error message ***
</pre>
{% endraw %}
