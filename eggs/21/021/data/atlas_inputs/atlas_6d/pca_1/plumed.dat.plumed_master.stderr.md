**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/atlas_6d/pca_1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az1016-35:07843] *** Process received signal ***
[fv-az1016-35:07843] Signal: Aborted (6)
[fv-az1016-35:07843] Signal code:  (-6)
[fv-az1016-35:07843] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f78a5842520]
[fv-az1016-35:07843] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f78a58969fc]
[fv-az1016-35:07843] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f78a5842476]
[fv-az1016-35:07843] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f78a58287f3]
[fv-az1016-35:07843] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f78a5ca2b9e]
[fv-az1016-35:07843] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f78a5cae20c]
[fv-az1016-35:07843] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f78a5cae277]
[fv-az1016-35:07843] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f78a5cae52b]
[fv-az1016-35:07843] [ 8] plumed_master(+0x14254)[0x5642b66b6254]
[fv-az1016-35:07843] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f78a5829d90]
[fv-az1016-35:07843] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f78a5829e40]
[fv-az1016-35:07843] [11] plumed_master(+0x14eb5)[0x5642b66b6eb5]
[fv-az1016-35:07843] *** End of error message ***
</pre>
{% endraw %}
