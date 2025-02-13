**Project ID:** [plumID:23.016]({{ '/' | absolute_url }}eggs/23/016/)  
Stderr for source:  plumed_reweight_microsw_adr_bin.dat   
Download: [zipped raw stdout](plumed_reweight_microsw_adr_bin.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_microsw_adr_bin.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @173 : keyword ARG is compulsory for this action
[fv-az2035-366:07079] *** Process received signal ***
[fv-az2035-366:07079] Signal: Aborted (6)
[fv-az2035-366:07079] Signal code:  (-6)
[fv-az2035-366:07079] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5bbb445330]
[fv-az2035-366:07079] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5bbb49eb2c]
[fv-az2035-366:07079] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5bbb44527e]
[fv-az2035-366:07079] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5bbb4288ff]
[fv-az2035-366:07079] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5bbb8a5ff5]
[fv-az2035-366:07079] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5bbb8bb0da]
[fv-az2035-366:07079] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5bbb8a5a55]
[fv-az2035-366:07079] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5bbb8a5a6f]
[fv-az2035-366:07079] [ 8] plumed_master(+0x146dd)[0x55ab644ae6dd]
[fv-az2035-366:07079] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5bbb42a1ca]
[fv-az2035-366:07079] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5bbb42a28b]
[fv-az2035-366:07079] [11] plumed_master(+0x15365)[0x55ab644af365]
[fv-az2035-366:07079] *** End of error message ***
</pre>
{% endraw %}
