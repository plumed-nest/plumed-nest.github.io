**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  FFH_scripts/plumed_FFH.dat   
Download: [zipped raw stdout](plumed_FFH.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_FFH.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az1016-35:07625] *** Process received signal ***
[fv-az1016-35:07625] Signal: Aborted (6)
[fv-az1016-35:07625] Signal code:  (-6)
[fv-az1016-35:07625] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f06d7c42520]
[fv-az1016-35:07625] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f06d7c969fc]
[fv-az1016-35:07625] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f06d7c42476]
[fv-az1016-35:07625] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f06d7c287f3]
[fv-az1016-35:07625] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f06d80a2b9e]
[fv-az1016-35:07625] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f06d80ae20c]
[fv-az1016-35:07625] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f06d80ae277]
[fv-az1016-35:07625] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f06d80ae52b]
[fv-az1016-35:07625] [ 8] plumed_master(+0x14254)[0x5602786ac254]
[fv-az1016-35:07625] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f06d7c29d90]
[fv-az1016-35:07625] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f06d7c29e40]
[fv-az1016-35:07625] [11] plumed_master(+0x14eb5)[0x5602786aceb5]
[fv-az1016-35:07625] *** End of error message ***
</pre>
{% endraw %}
