**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/convegence_double_well_1D/WTmetaD_adapt/plumed_WTmetaD_adaptive.dat   
Download: [zipped raw stdout](plumed_WTmetaD_adaptive.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_WTmetaD_adaptive.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[fv-az802-461:10666] *** Process received signal ***
[fv-az802-461:10666] Signal: Aborted (6)
[fv-az802-461:10666] Signal code:  (-6)
[fv-az802-461:10666] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fe109242520]
[fv-az802-461:10666] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fe1092969fc]
[fv-az802-461:10666] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fe109242476]
[fv-az802-461:10666] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fe1092287f3]
[fv-az802-461:10666] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fe1096a2b9e]
[fv-az802-461:10666] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fe1096ae20c]
[fv-az802-461:10666] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fe1096ae277]
[fv-az802-461:10666] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fe1096ae52b]
[fv-az802-461:10666] [ 8] plumed(+0x14254)[0x564e482e6254]
[fv-az802-461:10666] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fe109229d90]
[fv-az802-461:10666] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fe109229e40]
[fv-az802-461:10666] [11] plumed(+0x14eb5)[0x564e482e6eb5]
[fv-az802-461:10666] *** End of error message ***
</pre>
{% endraw %}
