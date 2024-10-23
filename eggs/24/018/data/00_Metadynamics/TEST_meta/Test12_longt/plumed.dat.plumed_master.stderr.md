**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test12_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1442-469:03948] *** Process received signal ***
[fv-az1442-469:03948] Signal: Aborted (6)
[fv-az1442-469:03948] Signal code:  (-6)
[fv-az1442-469:03948] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f3941e42520]
[fv-az1442-469:03948] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f3941e969fc]
[fv-az1442-469:03948] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f3941e42476]
[fv-az1442-469:03948] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f3941e287f3]
[fv-az1442-469:03948] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f39422a2b9e]
[fv-az1442-469:03948] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f39422ae20c]
[fv-az1442-469:03948] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f39422ae277]
[fv-az1442-469:03948] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f39422ae52b]
[fv-az1442-469:03948] [ 8] plumed_master(+0x14254)[0x5561b762e254]
[fv-az1442-469:03948] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f3941e29d90]
[fv-az1442-469:03948] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f3941e29e40]
[fv-az1442-469:03948] [11] plumed_master(+0x14eb5)[0x5561b762eeb5]
[fv-az1442-469:03948] *** End of error message ***
</pre>
{% endraw %}
