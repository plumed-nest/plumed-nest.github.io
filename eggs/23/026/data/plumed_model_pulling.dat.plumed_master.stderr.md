**Project ID:** [plumID:23.026]({{ '/' | absolute_url }}eggs/23/026/)  
Stderr for source:  plumed_model_pulling.dat   
Download: [zipped raw stdout](plumed_model_pulling.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_model_pulling.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[fv-az1429-284:03957] *** Process received signal ***
[fv-az1429-284:03957] Signal: Aborted (6)
[fv-az1429-284:03957] Signal code:  (-6)
[fv-az1429-284:03957] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fe1bfa42520]
[fv-az1429-284:03957] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fe1bfa969fc]
[fv-az1429-284:03957] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fe1bfa42476]
[fv-az1429-284:03957] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fe1bfa287f3]
[fv-az1429-284:03957] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fe1bfea2b9e]
[fv-az1429-284:03957] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fe1bfeae20c]
[fv-az1429-284:03957] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fe1bfeae277]
[fv-az1429-284:03957] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fe1bfeae52b]
[fv-az1429-284:03957] [ 8] plumed_master(+0x14254)[0x55b19ff90254]
[fv-az1429-284:03957] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fe1bfa29d90]
[fv-az1429-284:03957] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fe1bfa29e40]
[fv-az1429-284:03957] [11] plumed_master(+0x14eb5)[0x55b19ff90eb5]
[fv-az1429-284:03957] *** End of error message ***
</pre>
{% endraw %}
