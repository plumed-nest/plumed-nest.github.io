**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/atlas_3d/pca_1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az1016-35:07741] *** Process received signal ***
[fv-az1016-35:07741] Signal: Aborted (6)
[fv-az1016-35:07741] Signal code:  (-6)
[fv-az1016-35:07741] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f211b442520]
[fv-az1016-35:07741] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f211b4969fc]
[fv-az1016-35:07741] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f211b442476]
[fv-az1016-35:07741] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f211b4287f3]
[fv-az1016-35:07741] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f211b8a2b9e]
[fv-az1016-35:07741] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f211b8ae20c]
[fv-az1016-35:07741] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f211b8ae277]
[fv-az1016-35:07741] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f211b8ae52b]
[fv-az1016-35:07741] [ 8] plumed(+0x14254)[0x55930876d254]
[fv-az1016-35:07741] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f211b429d90]
[fv-az1016-35:07741] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f211b429e40]
[fv-az1016-35:07741] [11] plumed(+0x14eb5)[0x55930876deb5]
[fv-az1016-35:07741] *** End of error message ***
</pre>
{% endraw %}
