**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/convegence_double_well_1D/WTmetaD_adapt/plumed_WTmetaD_adaptive.dat   
Download: [zipped raw stdout](plumed_WTmetaD_adaptive.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_WTmetaD_adaptive.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[pkrvmbietmlfzoi:12249] *** Process received signal ***
[pkrvmbietmlfzoi:12249] Signal: Aborted (6)
[pkrvmbietmlfzoi:12249] Signal code:  (-6)
[pkrvmbietmlfzoi:12249] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f41ec045330]
[pkrvmbietmlfzoi:12249] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f41ec09eb2c]
[pkrvmbietmlfzoi:12249] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f41ec04527e]
[pkrvmbietmlfzoi:12249] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f41ec0288ff]
[pkrvmbietmlfzoi:12249] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f41ec4a5ff5]
[pkrvmbietmlfzoi:12249] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f41ec4bb0da]
[pkrvmbietmlfzoi:12249] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f41ec4a5a55]
[pkrvmbietmlfzoi:12249] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f41ec4a5a6f]
[pkrvmbietmlfzoi:12249] [ 8] plumed_master(+0x146dd)[0x556a51da86dd]
[pkrvmbietmlfzoi:12249] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f41ec02a1ca]
[pkrvmbietmlfzoi:12249] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f41ec02a28b]
[pkrvmbietmlfzoi:12249] [11] plumed_master(+0x15365)[0x556a51da9365]
[pkrvmbietmlfzoi:12249] *** End of error message ***
</pre>
{% endraw %}
