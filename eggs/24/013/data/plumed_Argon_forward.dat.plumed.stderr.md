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
[pkrvmq0rgcvqdmg:06941] *** Process received signal ***
[pkrvmq0rgcvqdmg:06941] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:06941] Signal code:  (-6)
[pkrvmq0rgcvqdmg:06941] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff911a45330]
[pkrvmq0rgcvqdmg:06941] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff911a9eb2c]
[pkrvmq0rgcvqdmg:06941] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff911a4527e]
[pkrvmq0rgcvqdmg:06941] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff911a288ff]
[pkrvmq0rgcvqdmg:06941] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff911ea5ff5]
[pkrvmq0rgcvqdmg:06941] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff911ebb0da]
[pkrvmq0rgcvqdmg:06941] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff911ea5a55]
[pkrvmq0rgcvqdmg:06941] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff911ea5a6f]
[pkrvmq0rgcvqdmg:06941] [ 8] plumed(+0x146dd)[0x5636dd9996dd]
[pkrvmq0rgcvqdmg:06941] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff911a2a1ca]
[pkrvmq0rgcvqdmg:06941] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff911a2a28b]
[pkrvmq0rgcvqdmg:06941] [11] plumed(+0x15365)[0x5636dd99a365]
[pkrvmq0rgcvqdmg:06941] *** End of error message ***
</pre>
{% endraw %}
