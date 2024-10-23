**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/atlas_3d/pca_2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az1016-35:07772] *** Process received signal ***
[fv-az1016-35:07772] Signal: Aborted (6)
[fv-az1016-35:07772] Signal code:  (-6)
[fv-az1016-35:07772] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fc2a1042520]
[fv-az1016-35:07772] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fc2a10969fc]
[fv-az1016-35:07772] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fc2a1042476]
[fv-az1016-35:07772] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fc2a10287f3]
[fv-az1016-35:07772] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fc2a14a2b9e]
[fv-az1016-35:07772] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fc2a14ae20c]
[fv-az1016-35:07772] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fc2a14ae277]
[fv-az1016-35:07772] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fc2a14ae52b]
[fv-az1016-35:07772] [ 8] plumed(+0x14254)[0x5566b6ff5254]
[fv-az1016-35:07772] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fc2a1029d90]
[fv-az1016-35:07772] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fc2a1029e40]
[fv-az1016-35:07772] [11] plumed(+0x14eb5)[0x5566b6ff5eb5]
[fv-az1016-35:07772] *** End of error message ***
</pre>
{% endraw %}
