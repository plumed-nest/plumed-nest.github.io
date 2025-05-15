**Project ID:** [plumID:19.017]({{ '/' | absolute_url }}eggs/19/017/)  
Stderr for source:  plumed_reweight/reweight_rho_c.dat   
Download: [zipped raw stdout](reweight_rho_c.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweight_rho_c.dat.plumed_master.stderr.txt.zip) 
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
ERROR in input to action DUMPGRID with label @17 : keyword ARG is compulsory for this action
[pkrvmberfyhpb9w:14866] *** Process received signal ***
[pkrvmberfyhpb9w:14866] Signal: Aborted (6)
[pkrvmberfyhpb9w:14866] Signal code:  (-6)
[pkrvmberfyhpb9w:14866] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f708d845330]
[pkrvmberfyhpb9w:14866] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f708d89eb2c]
[pkrvmberfyhpb9w:14866] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f708d84527e]
[pkrvmberfyhpb9w:14866] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f708d8288ff]
[pkrvmberfyhpb9w:14866] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f708dca5ff5]
[pkrvmberfyhpb9w:14866] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f708dcbb0da]
[pkrvmberfyhpb9w:14866] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f708dca5a55]
[pkrvmberfyhpb9w:14866] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f708dca5a6f]
[pkrvmberfyhpb9w:14866] [ 8] plumed_master(+0x146dd)[0x55aca81156dd]
[pkrvmberfyhpb9w:14866] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f708d82a1ca]
[pkrvmberfyhpb9w:14866] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f708d82a28b]
[pkrvmberfyhpb9w:14866] [11] plumed_master(+0x15365)[0x55aca8116365]
[pkrvmberfyhpb9w:14866] *** End of error message ***
</pre>
{% endraw %}
