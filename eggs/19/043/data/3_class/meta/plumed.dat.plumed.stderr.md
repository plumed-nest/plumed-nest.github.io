**Project ID:** [plumID:19.043]({{ '/' | absolute_url }}eggs/19/043/)  
Stderr for source:  3_class/meta/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[fv-az1210-136:71799] *** Process received signal ***
[fv-az1210-136:71799] Signal: Aborted (6)
[fv-az1210-136:71799] Signal code:  (-6)
[fv-az1210-136:71799] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f05f0042520]
[fv-az1210-136:71799] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f05f00969fc]
[fv-az1210-136:71799] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f05f0042476]
[fv-az1210-136:71799] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f05f00287f3]
[fv-az1210-136:71799] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f05f04a4f26]
[fv-az1210-136:71799] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f05f04b6d9c]
[fv-az1210-136:71799] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f05f04b6e07]
[fv-az1210-136:71799] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f05f04b70bb]
[fv-az1210-136:71799] [ 8] plumed(+0x12f48)[0x55e45caa6f48]
[fv-az1210-136:71799] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f05f0029d90]
[fv-az1210-136:71799] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f05f0029e40]
[fv-az1210-136:71799] [11] plumed(+0x131e5)[0x55e45caa71e5]
[fv-az1210-136:71799] *** End of error message ***
</pre>
{% endraw %}
