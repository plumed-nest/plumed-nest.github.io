**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/atlas_2d/pca_2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az1016-35:07710] *** Process received signal ***
[fv-az1016-35:07710] Signal: Aborted (6)
[fv-az1016-35:07710] Signal code:  (-6)
[fv-az1016-35:07710] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f5542842520]
[fv-az1016-35:07710] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f55428969fc]
[fv-az1016-35:07710] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f5542842476]
[fv-az1016-35:07710] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f55428287f3]
[fv-az1016-35:07710] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f5542ca2b9e]
[fv-az1016-35:07710] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f5542cae20c]
[fv-az1016-35:07710] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f5542cae277]
[fv-az1016-35:07710] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f5542cae52b]
[fv-az1016-35:07710] [ 8] plumed(+0x14254)[0x55b5092c8254]
[fv-az1016-35:07710] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f5542829d90]
[fv-az1016-35:07710] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f5542829e40]
[fv-az1016-35:07710] [11] plumed(+0x14eb5)[0x55b5092c8eb5]
[fv-az1016-35:07710] *** End of error message ***
</pre>
{% endraw %}
