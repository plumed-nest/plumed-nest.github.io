**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  ohco2/asymm-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @24 : keyword ARG is compulsory for this action
[runnervmeorf1:10839] *** Process received signal ***
[runnervmeorf1:10839] Signal: Aborted (6)
[runnervmeorf1:10839] Signal code:  (-6)
[runnervmeorf1:10839] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fde22245330]
[runnervmeorf1:10839] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fde2229eb2c]
[runnervmeorf1:10839] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fde2224527e]
[runnervmeorf1:10839] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fde222288ff]
[runnervmeorf1:10839] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fde226a5ff5]
[runnervmeorf1:10839] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fde226bb0da]
[runnervmeorf1:10839] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fde226a5a55]
[runnervmeorf1:10839] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fde226a5a6f]
[runnervmeorf1:10839] [ 8] plumed_master(+0x146dd)[0x55e6b00576dd]
[runnervmeorf1:10839] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fde2222a1ca]
[runnervmeorf1:10839] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fde2222a28b]
[runnervmeorf1:10839] [11] plumed_master(+0x15365)[0x55e6b0058365]
[runnervmeorf1:10839] *** End of error message ***
</pre>
{% endraw %}
