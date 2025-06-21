**Project ID:** [plumID:23.016]({{ '/' | absolute_url }}eggs/23/016/)  
Stderr for source:  plumed_reweight_microsw_adr_bin.dat   
Download: [zipped raw stdout](plumed_reweight_microsw_adr_bin.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_microsw_adr_bin.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @167 : keyword ARG is compulsory for this action
[pkrvmxyh4eaekms:06588] *** Process received signal ***
[pkrvmxyh4eaekms:06588] Signal: Aborted (6)
[pkrvmxyh4eaekms:06588] Signal code:  (-6)
[pkrvmxyh4eaekms:06588] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa514045330]
[pkrvmxyh4eaekms:06588] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa51409eb2c]
[pkrvmxyh4eaekms:06588] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa51404527e]
[pkrvmxyh4eaekms:06588] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa5140288ff]
[pkrvmxyh4eaekms:06588] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa5144a5ff5]
[pkrvmxyh4eaekms:06588] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa5144bb0da]
[pkrvmxyh4eaekms:06588] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa5144a5a55]
[pkrvmxyh4eaekms:06588] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa5144a5a6f]
[pkrvmxyh4eaekms:06588] [ 8] plumed_master(+0x146dd)[0x55644ef366dd]
[pkrvmxyh4eaekms:06588] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa51402a1ca]
[pkrvmxyh4eaekms:06588] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa51402a28b]
[pkrvmxyh4eaekms:06588] [11] plumed_master(+0x15365)[0x55644ef37365]
[pkrvmxyh4eaekms:06588] *** End of error message ***
</pre>
{% endraw %}
