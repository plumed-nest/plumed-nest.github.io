**Project ID:** [plumID:23.016]({{ '/' | absolute_url }}eggs/23/016/)  
Stderr for source:  plumed_reweight_2D_microsw_adr_bin.dat   
Download: [zipped raw stdout](plumed_reweight_2D_microsw_adr_bin.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_2D_microsw_adr_bin.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @87 : keyword ARG is compulsory for this action
[pkrvmxyh4eaekms:06550] *** Process received signal ***
[pkrvmxyh4eaekms:06550] Signal: Aborted (6)
[pkrvmxyh4eaekms:06550] Signal code:  (-6)
[pkrvmxyh4eaekms:06550] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6de8245330]
[pkrvmxyh4eaekms:06550] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6de829eb2c]
[pkrvmxyh4eaekms:06550] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6de824527e]
[pkrvmxyh4eaekms:06550] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6de82288ff]
[pkrvmxyh4eaekms:06550] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6de86a5ff5]
[pkrvmxyh4eaekms:06550] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6de86bb0da]
[pkrvmxyh4eaekms:06550] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6de86a5a55]
[pkrvmxyh4eaekms:06550] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6de86a5a6f]
[pkrvmxyh4eaekms:06550] [ 8] plumed_master(+0x146dd)[0x565184e886dd]
[pkrvmxyh4eaekms:06550] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6de822a1ca]
[pkrvmxyh4eaekms:06550] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6de822a28b]
[pkrvmxyh4eaekms:06550] [11] plumed_master(+0x15365)[0x565184e89365]
[pkrvmxyh4eaekms:06550] *** End of error message ***
</pre>
{% endraw %}
