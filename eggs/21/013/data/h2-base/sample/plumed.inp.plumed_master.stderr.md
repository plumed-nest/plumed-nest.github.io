**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  h2-base/sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @18 : keyword ARG is compulsory for this action
[runnervmeorf1:08498] *** Process received signal ***
[runnervmeorf1:08498] Signal: Aborted (6)
[runnervmeorf1:08498] Signal code:  (-6)
[runnervmeorf1:08498] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f45c3e45330]
[runnervmeorf1:08498] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f45c3e9eb2c]
[runnervmeorf1:08498] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f45c3e4527e]
[runnervmeorf1:08498] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f45c3e288ff]
[runnervmeorf1:08498] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f45c42a5ff5]
[runnervmeorf1:08498] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f45c42bb0da]
[runnervmeorf1:08498] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f45c42a5a55]
[runnervmeorf1:08498] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f45c42a5a6f]
[runnervmeorf1:08498] [ 8] plumed_master(+0x146dd)[0x5573cd5736dd]
[runnervmeorf1:08498] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f45c3e2a1ca]
[runnervmeorf1:08498] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f45c3e2a28b]
[runnervmeorf1:08498] [11] plumed_master(+0x15365)[0x5573cd574365]
[runnervmeorf1:08498] *** End of error message ***
</pre>
{% endraw %}
