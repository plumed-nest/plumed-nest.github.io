**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test11_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1442-469:03907] *** Process received signal ***
[fv-az1442-469:03907] Signal: Aborted (6)
[fv-az1442-469:03907] Signal code:  (-6)
[fv-az1442-469:03907] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f7c9c642520]
[fv-az1442-469:03907] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f7c9c6969fc]
[fv-az1442-469:03907] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f7c9c642476]
[fv-az1442-469:03907] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f7c9c6287f3]
[fv-az1442-469:03907] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f7c9caa2b9e]
[fv-az1442-469:03907] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f7c9caae20c]
[fv-az1442-469:03907] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f7c9caae277]
[fv-az1442-469:03907] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f7c9caae52b]
[fv-az1442-469:03907] [ 8] plumed(+0x14254)[0x55c30ba88254]
[fv-az1442-469:03907] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f7c9c629d90]
[fv-az1442-469:03907] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f7c9c629e40]
[fv-az1442-469:03907] [11] plumed(+0x14eb5)[0x55c30ba88eb5]
[fv-az1442-469:03907] *** End of error message ***
</pre>
{% endraw %}
