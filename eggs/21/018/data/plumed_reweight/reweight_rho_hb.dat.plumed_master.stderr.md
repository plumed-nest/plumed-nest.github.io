**Project ID:** [plumID:21.018]({{ '/' | absolute_url }}eggs/21/018/)  
Stderr for source:  plumed_reweight/reweight_rho_hb.dat   
Download: [zipped raw stdout](reweight_rho_hb.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweight_rho_hb.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
WARNING: IFile closed in the middle of reading. seems strange!
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @34 : keyword ARG is compulsory for this action
[pkrvmberfyhpb9w:10883] *** Process received signal ***
[pkrvmberfyhpb9w:10883] Signal: Aborted (6)
[pkrvmberfyhpb9w:10883] Signal code:  (-6)
[pkrvmberfyhpb9w:10883] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8154845330]
[pkrvmberfyhpb9w:10883] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f815489eb2c]
[pkrvmberfyhpb9w:10883] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f815484527e]
[pkrvmberfyhpb9w:10883] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f81548288ff]
[pkrvmberfyhpb9w:10883] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8154ca5ff5]
[pkrvmberfyhpb9w:10883] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8154cbb0da]
[pkrvmberfyhpb9w:10883] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8154ca5a55]
[pkrvmberfyhpb9w:10883] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8154ca5a6f]
[pkrvmberfyhpb9w:10883] [ 8] plumed_master(+0x146dd)[0x55baa0d596dd]
[pkrvmberfyhpb9w:10883] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f815482a1ca]
[pkrvmberfyhpb9w:10883] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f815482a28b]
[pkrvmberfyhpb9w:10883] [11] plumed_master(+0x15365)[0x55baa0d5a365]
[pkrvmberfyhpb9w:10883] *** End of error message ***
</pre>
{% endraw %}
