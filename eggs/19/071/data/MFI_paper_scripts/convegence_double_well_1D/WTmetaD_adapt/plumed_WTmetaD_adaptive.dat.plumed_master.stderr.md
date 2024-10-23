**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/convegence_double_well_1D/WTmetaD_adapt/plumed_WTmetaD_adaptive.dat   
Download: [zipped raw stdout](plumed_WTmetaD_adaptive.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_WTmetaD_adaptive.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[fv-az802-461:10674] *** Process received signal ***
[fv-az802-461:10674] Signal: Aborted (6)
[fv-az802-461:10674] Signal code:  (-6)
[fv-az802-461:10674] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f4e24a42520]
[fv-az802-461:10674] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f4e24a969fc]
[fv-az802-461:10674] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f4e24a42476]
[fv-az802-461:10674] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f4e24a287f3]
[fv-az802-461:10674] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f4e24ea2b9e]
[fv-az802-461:10674] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f4e24eae20c]
[fv-az802-461:10674] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f4e24eae277]
[fv-az802-461:10674] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f4e24eae52b]
[fv-az802-461:10674] [ 8] plumed_master(+0x14254)[0x5570ad618254]
[fv-az802-461:10674] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f4e24a29d90]
[fv-az802-461:10674] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f4e24a29e40]
[fv-az802-461:10674] [11] plumed_master(+0x14eb5)[0x5570ad618eb5]
[fv-az802-461:10674] *** End of error message ***
</pre>
{% endraw %}
