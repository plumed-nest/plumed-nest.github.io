**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-base/asymm-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @32 : keyword ARG is compulsory for this action
[runnervmeorf1:07755] *** Process received signal ***
[runnervmeorf1:07755] Signal: Aborted (6)
[runnervmeorf1:07755] Signal code:  (-6)
[runnervmeorf1:07755] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff59ee45330]
[runnervmeorf1:07755] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff59ee9eb2c]
[runnervmeorf1:07755] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff59ee4527e]
[runnervmeorf1:07755] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff59ee288ff]
[runnervmeorf1:07755] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff59f2a5ff5]
[runnervmeorf1:07755] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff59f2bb0da]
[runnervmeorf1:07755] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff59f2a5a55]
[runnervmeorf1:07755] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff59f2a5a6f]
[runnervmeorf1:07755] [ 8] plumed_master(+0x146dd)[0x55a62dc776dd]
[runnervmeorf1:07755] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff59ee2a1ca]
[runnervmeorf1:07755] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff59ee2a28b]
[runnervmeorf1:07755] [11] plumed_master(+0x15365)[0x55a62dc78365]
[runnervmeorf1:07755] *** End of error message ***
</pre>
{% endraw %}
