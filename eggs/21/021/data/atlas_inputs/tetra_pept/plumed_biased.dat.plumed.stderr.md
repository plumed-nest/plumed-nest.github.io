**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/tetra_pept/plumed_biased.dat   
Download: [zipped raw stdout](plumed_biased.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_biased.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az1016-35:07963] *** Process received signal ***
[fv-az1016-35:07963] Signal: Aborted (6)
[fv-az1016-35:07963] Signal code:  (-6)
[fv-az1016-35:07963] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f67b8e42520]
[fv-az1016-35:07963] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f67b8e969fc]
[fv-az1016-35:07963] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f67b8e42476]
[fv-az1016-35:07963] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f67b8e287f3]
[fv-az1016-35:07963] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f67b92a2b9e]
[fv-az1016-35:07963] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f67b92ae20c]
[fv-az1016-35:07963] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f67b92ae277]
[fv-az1016-35:07963] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f67b92ae52b]
[fv-az1016-35:07963] [ 8] plumed(+0x14254)[0x55c1504cf254]
[fv-az1016-35:07963] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f67b8e29d90]
[fv-az1016-35:07963] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f67b8e29e40]
[fv-az1016-35:07963] [11] plumed(+0x14eb5)[0x55c1504cfeb5]
[fv-az1016-35:07963] *** End of error message ***
</pre>
{% endraw %}