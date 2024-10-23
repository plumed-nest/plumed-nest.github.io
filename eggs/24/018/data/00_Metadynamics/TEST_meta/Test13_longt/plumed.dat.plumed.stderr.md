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
[fv-az1442-469:03971] *** Process received signal ***
[fv-az1442-469:03971] Signal: Aborted (6)
[fv-az1442-469:03971] Signal code:  (-6)
[fv-az1442-469:03971] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f3f40a42520]
[fv-az1442-469:03971] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f3f40a969fc]
[fv-az1442-469:03971] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f3f40a42476]
[fv-az1442-469:03971] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f3f40a287f3]
[fv-az1442-469:03971] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f3f40ea2b9e]
[fv-az1442-469:03971] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f3f40eae20c]
[fv-az1442-469:03971] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f3f40eae277]
[fv-az1442-469:03971] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f3f40eae52b]
[fv-az1442-469:03971] [ 8] plumed(+0x14254)[0x55e927ec3254]
[fv-az1442-469:03971] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f3f40a29d90]
[fv-az1442-469:03971] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f3f40a29e40]
[fv-az1442-469:03971] [11] plumed(+0x14eb5)[0x55e927ec3eb5]
[fv-az1442-469:03971] *** End of error message ***
</pre>
{% endraw %}
