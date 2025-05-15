**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_reweight.dat   
Download: [zipped raw stdout](plumed_reweight.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[pkrvmberfyhpb9w:06183] *** Process received signal ***
[pkrvmberfyhpb9w:06183] Signal: Aborted (6)
[pkrvmberfyhpb9w:06183] Signal code:  (-6)
[pkrvmberfyhpb9w:06183] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7ace645330]
[pkrvmberfyhpb9w:06183] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7ace69eb2c]
[pkrvmberfyhpb9w:06183] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7ace64527e]
[pkrvmberfyhpb9w:06183] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7ace6288ff]
[pkrvmberfyhpb9w:06183] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7aceaa5ff5]
[pkrvmberfyhpb9w:06183] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7aceabb0da]
[pkrvmberfyhpb9w:06183] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7aceaa5a55]
[pkrvmberfyhpb9w:06183] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7aceaa5a6f]
[pkrvmberfyhpb9w:06183] [ 8] plumed_master(+0x146dd)[0x557d189ec6dd]
[pkrvmberfyhpb9w:06183] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7ace62a1ca]
[pkrvmberfyhpb9w:06183] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7ace62a28b]
[pkrvmberfyhpb9w:06183] [11] plumed_master(+0x15365)[0x557d189ed365]
[pkrvmberfyhpb9w:06183] *** End of error message ***
</pre>
{% endraw %}
