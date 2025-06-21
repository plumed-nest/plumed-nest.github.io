**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT_A399V/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @34 : keyword ARG is compulsory for this action
[pkrvmxyh4eaekms:06078] *** Process received signal ***
[pkrvmxyh4eaekms:06078] Signal: Aborted (6)
[pkrvmxyh4eaekms:06078] Signal code:  (-6)
[pkrvmxyh4eaekms:06078] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb3c1a45330]
[pkrvmxyh4eaekms:06078] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb3c1a9eb2c]
[pkrvmxyh4eaekms:06078] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb3c1a4527e]
[pkrvmxyh4eaekms:06078] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb3c1a288ff]
[pkrvmxyh4eaekms:06078] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb3c1ea5ff5]
[pkrvmxyh4eaekms:06078] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb3c1ebb0da]
[pkrvmxyh4eaekms:06078] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb3c1ea5a55]
[pkrvmxyh4eaekms:06078] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb3c1ea5a6f]
[pkrvmxyh4eaekms:06078] [ 8] plumed_master(+0x146dd)[0x55b0c1e7c6dd]
[pkrvmxyh4eaekms:06078] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb3c1a2a1ca]
[pkrvmxyh4eaekms:06078] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb3c1a2a28b]
[pkrvmxyh4eaekms:06078] [11] plumed_master(+0x15365)[0x55b0c1e7d365]
[pkrvmxyh4eaekms:06078] *** End of error message ***
</pre>
{% endraw %}
