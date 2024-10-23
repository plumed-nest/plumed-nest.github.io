**Project ID:** [plumID:23.043]({{ '/' | absolute_url }}eggs/23/043/)  
Stderr for source:  metad-example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "SPHERICAL_EXPANSION" is not known.
[fv-az1016-35:05376] *** Process received signal ***
[fv-az1016-35:05376] Signal: Aborted (6)
[fv-az1016-35:05376] Signal code:  (-6)
[fv-az1016-35:05376] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f942f442520]
[fv-az1016-35:05376] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f942f4969fc]
[fv-az1016-35:05376] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f942f442476]
[fv-az1016-35:05376] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f942f4287f3]
[fv-az1016-35:05376] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f942f8a2b9e]
[fv-az1016-35:05376] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f942f8ae20c]
[fv-az1016-35:05376] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f942f8ae277]
[fv-az1016-35:05376] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f942f8ae52b]
[fv-az1016-35:05376] [ 8] plumed_master(+0x14254)[0x55b183726254]
[fv-az1016-35:05376] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f942f429d90]
[fv-az1016-35:05376] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f942f429e40]
[fv-az1016-35:05376] [11] plumed_master(+0x14eb5)[0x55b183726eb5]
[fv-az1016-35:05376] *** End of error message ***
</pre>
{% endraw %}
