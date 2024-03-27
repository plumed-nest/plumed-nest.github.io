**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_mo.dat   
Download: [zipped raw stdout](plumed_mo.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_mo.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action DISTANCE with label @0 : Number of specified atoms should be 2
[fv-az1487-606:72594] *** Process received signal ***
[fv-az1487-606:72594] Signal: Aborted (6)
[fv-az1487-606:72594] Signal code:  (-6)
[fv-az1487-606:72594] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fa905442520]
[fv-az1487-606:72594] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fa9054969fc]
[fv-az1487-606:72594] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fa905442476]
[fv-az1487-606:72594] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fa9054287f3]
[fv-az1487-606:72594] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7fa9058a4f26]
[fv-az1487-606:72594] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7fa9058b6d9c]
[fv-az1487-606:72594] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7fa9058b6e07]
[fv-az1487-606:72594] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fa9058b70bb]
[fv-az1487-606:72594] [ 8] plumed(+0x12f48)[0x556433109f48]
[fv-az1487-606:72594] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fa905429d90]
[fv-az1487-606:72594] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fa905429e40]
[fv-az1487-606:72594] [11] plumed(+0x131e5)[0x55643310a1e5]
[fv-az1487-606:72594] *** End of error message ***
</pre>
{% endraw %}
