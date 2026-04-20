**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-base/symm-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @34 : keyword ARG is compulsory for this action
[runnervmeorf1:07820] *** Process received signal ***
[runnervmeorf1:07820] Signal: Aborted (6)
[runnervmeorf1:07820] Signal code:  (-6)
[runnervmeorf1:07820] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1757c45330]
[runnervmeorf1:07820] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1757c9eb2c]
[runnervmeorf1:07820] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1757c4527e]
[runnervmeorf1:07820] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1757c288ff]
[runnervmeorf1:07820] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f17580a5ff5]
[runnervmeorf1:07820] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f17580bb0da]
[runnervmeorf1:07820] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f17580a5a55]
[runnervmeorf1:07820] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f17580a5a6f]
[runnervmeorf1:07820] [ 8] plumed_master(+0x146dd)[0x55a43a2506dd]
[runnervmeorf1:07820] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1757c2a1ca]
[runnervmeorf1:07820] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1757c2a28b]
[runnervmeorf1:07820] [11] plumed_master(+0x15365)[0x55a43a251365]
[runnervmeorf1:07820] *** End of error message ***
</pre>
{% endraw %}
