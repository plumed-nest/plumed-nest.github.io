**Project ID:** [plumID:22.006]({{ '/' | absolute_url }}eggs/22/006/)  
Stderr for source:  analysis/contacts.plumed   
Download: [zipped raw stdout](contacts.plumed.plumed_master.stdout.txt.zip) - [zipped raw stderr](contacts.plumed.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @88 : keyword ARG is compulsory for this action
[pkrvmq0rgcvqdmg:07518] *** Process received signal ***
[pkrvmq0rgcvqdmg:07518] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:07518] Signal code:  (-6)
[pkrvmq0rgcvqdmg:07518] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff17c245330]
[pkrvmq0rgcvqdmg:07518] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff17c29eb2c]
[pkrvmq0rgcvqdmg:07518] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff17c24527e]
[pkrvmq0rgcvqdmg:07518] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff17c2288ff]
[pkrvmq0rgcvqdmg:07518] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff17c6a5ff5]
[pkrvmq0rgcvqdmg:07518] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff17c6bb0da]
[pkrvmq0rgcvqdmg:07518] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff17c6a5a55]
[pkrvmq0rgcvqdmg:07518] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff17c6a5a6f]
[pkrvmq0rgcvqdmg:07518] [ 8] plumed_master(+0x146dd)[0x559f0c0f86dd]
[pkrvmq0rgcvqdmg:07518] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff17c22a1ca]
[pkrvmq0rgcvqdmg:07518] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff17c22a28b]
[pkrvmq0rgcvqdmg:07518] [11] plumed_master(+0x15365)[0x559f0c0f9365]
[pkrvmq0rgcvqdmg:07518] *** End of error message ***
</pre>
{% endraw %}
