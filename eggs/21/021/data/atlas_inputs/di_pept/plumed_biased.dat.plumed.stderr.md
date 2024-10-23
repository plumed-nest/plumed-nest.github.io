**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/di_pept/plumed_biased.dat   
Download: [zipped raw stdout](plumed_biased.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_biased.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az1016-35:07931] *** Process received signal ***
[fv-az1016-35:07931] Signal: Aborted (6)
[fv-az1016-35:07931] Signal code:  (-6)
[fv-az1016-35:07931] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fbc87e42520]
[fv-az1016-35:07931] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fbc87e969fc]
[fv-az1016-35:07931] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fbc87e42476]
[fv-az1016-35:07931] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fbc87e287f3]
[fv-az1016-35:07931] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fbc882a2b9e]
[fv-az1016-35:07931] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fbc882ae20c]
[fv-az1016-35:07931] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fbc882ae277]
[fv-az1016-35:07931] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fbc882ae52b]
[fv-az1016-35:07931] [ 8] plumed(+0x14254)[0x55838a2d4254]
[fv-az1016-35:07931] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fbc87e29d90]
[fv-az1016-35:07931] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fbc87e29e40]
[fv-az1016-35:07931] [11] plumed(+0x14eb5)[0x55838a2d4eb5]
[fv-az1016-35:07931] *** End of error message ***
</pre>
{% endraw %}
