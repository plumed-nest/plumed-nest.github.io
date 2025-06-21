**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_forward.dat   
Download: [zipped raw stdout](plumed_Argon_forward.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_forward.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[pkrvmxyh4eaekms:06281] *** Process received signal ***
[pkrvmxyh4eaekms:06281] Signal: Aborted (6)
[pkrvmxyh4eaekms:06281] Signal code:  (-6)
[pkrvmxyh4eaekms:06281] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe434a45330]
[pkrvmxyh4eaekms:06281] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe434a9eb2c]
[pkrvmxyh4eaekms:06281] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe434a4527e]
[pkrvmxyh4eaekms:06281] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe434a288ff]
[pkrvmxyh4eaekms:06281] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe434ea5ff5]
[pkrvmxyh4eaekms:06281] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe434ebb0da]
[pkrvmxyh4eaekms:06281] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe434ea5a55]
[pkrvmxyh4eaekms:06281] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe434ea5a6f]
[pkrvmxyh4eaekms:06281] [ 8] plumed(+0x146dd)[0x556803a676dd]
[pkrvmxyh4eaekms:06281] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe434a2a1ca]
[pkrvmxyh4eaekms:06281] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe434a2a28b]
[pkrvmxyh4eaekms:06281] [11] plumed(+0x15365)[0x556803a68365]
[pkrvmxyh4eaekms:06281] *** End of error message ***
</pre>
{% endraw %}
