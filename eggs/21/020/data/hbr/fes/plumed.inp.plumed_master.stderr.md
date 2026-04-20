**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  hbr/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @41 : keyword ARG is compulsory for this action
[runnervmeorf1:08347] *** Process received signal ***
[runnervmeorf1:08347] Signal: Aborted (6)
[runnervmeorf1:08347] Signal code:  (-6)
[runnervmeorf1:08347] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f51fb645330]
[runnervmeorf1:08347] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f51fb69eb2c]
[runnervmeorf1:08347] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f51fb64527e]
[runnervmeorf1:08347] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f51fb6288ff]
[runnervmeorf1:08347] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f51fbaa5ff5]
[runnervmeorf1:08347] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f51fbabb0da]
[runnervmeorf1:08347] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f51fbaa5a55]
[runnervmeorf1:08347] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f51fbaa5a6f]
[runnervmeorf1:08347] [ 8] plumed_master(+0x146dd)[0x5629f3e866dd]
[runnervmeorf1:08347] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f51fb62a1ca]
[runnervmeorf1:08347] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f51fb62a28b]
[runnervmeorf1:08347] [11] plumed_master(+0x15365)[0x5629f3e87365]
[runnervmeorf1:08347] *** End of error message ***
</pre>
{% endraw %}
