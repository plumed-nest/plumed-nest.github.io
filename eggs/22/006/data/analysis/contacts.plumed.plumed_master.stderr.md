**Project ID:** [plumID:22.006]({{ '/' | absolute_url }}eggs/22/006/)  
Stderr for source:  analysis/contacts.plumed   
Download: [zipped raw stdout](contacts.plumed.plumed_master.stdout.txt.zip) - [zipped raw stderr](contacts.plumed.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @69 : keyword ARG is compulsory for this action
[runnervmeorf1:06929] *** Process received signal ***
[runnervmeorf1:06929] Signal: Aborted (6)
[runnervmeorf1:06929] Signal code:  (-6)
[runnervmeorf1:06929] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fac01c45330]
[runnervmeorf1:06929] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fac01c9eb2c]
[runnervmeorf1:06929] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fac01c4527e]
[runnervmeorf1:06929] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fac01c288ff]
[runnervmeorf1:06929] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fac020a5ff5]
[runnervmeorf1:06929] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fac020bb0da]
[runnervmeorf1:06929] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fac020a5a55]
[runnervmeorf1:06929] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fac020a5a6f]
[runnervmeorf1:06929] [ 8] plumed_master(+0x146dd)[0x5633fae136dd]
[runnervmeorf1:06929] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fac01c2a1ca]
[runnervmeorf1:06929] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fac01c2a28b]
[runnervmeorf1:06929] [11] plumed_master(+0x15365)[0x5633fae14365]
[runnervmeorf1:06929] *** End of error message ***
</pre>
{% endraw %}
