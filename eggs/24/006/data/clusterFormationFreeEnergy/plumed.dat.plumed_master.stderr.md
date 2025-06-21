**Project ID:** [plumID:24.006]({{ '/' | absolute_url }}eggs/24/006/)  
Stderr for source:  clusterFormationFreeEnergy/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DFSCLUSTERING with label dfs : keyword ARG is compulsory for this action
[pkrvmxyh4eaekms:07920] *** Process received signal ***
[pkrvmxyh4eaekms:07920] Signal: Aborted (6)
[pkrvmxyh4eaekms:07920] Signal code:  (-6)
[pkrvmxyh4eaekms:07920] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5ce6845330]
[pkrvmxyh4eaekms:07920] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5ce689eb2c]
[pkrvmxyh4eaekms:07920] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5ce684527e]
[pkrvmxyh4eaekms:07920] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5ce68288ff]
[pkrvmxyh4eaekms:07920] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5ce6ca5ff5]
[pkrvmxyh4eaekms:07920] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5ce6cbb0da]
[pkrvmxyh4eaekms:07920] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5ce6ca5a55]
[pkrvmxyh4eaekms:07920] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5ce6ca5a6f]
[pkrvmxyh4eaekms:07920] [ 8] plumed_master(+0x146dd)[0x55ebe87026dd]
[pkrvmxyh4eaekms:07920] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5ce682a1ca]
[pkrvmxyh4eaekms:07920] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5ce682a28b]
[pkrvmxyh4eaekms:07920] [11] plumed_master(+0x15365)[0x55ebe8703365]
[pkrvmxyh4eaekms:07920] *** End of error message ***
</pre>
{% endraw %}
