**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  h3/sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @22 : keyword ARG is compulsory for this action
[runnervmeorf1:11347] *** Process received signal ***
[runnervmeorf1:11347] Signal: Aborted (6)
[runnervmeorf1:11347] Signal code:  (-6)
[runnervmeorf1:11347] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0530245330]
[runnervmeorf1:11347] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f053029eb2c]
[runnervmeorf1:11347] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f053024527e]
[runnervmeorf1:11347] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f05302288ff]
[runnervmeorf1:11347] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f05306a5ff5]
[runnervmeorf1:11347] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f05306bb0da]
[runnervmeorf1:11347] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f05306a5a55]
[runnervmeorf1:11347] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f05306a5a6f]
[runnervmeorf1:11347] [ 8] plumed_master(+0x146dd)[0x55f46811e6dd]
[runnervmeorf1:11347] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f053022a1ca]
[runnervmeorf1:11347] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f053022a28b]
[runnervmeorf1:11347] [11] plumed_master(+0x15365)[0x55f46811f365]
[runnervmeorf1:11347] *** End of error message ***
</pre>
{% endraw %}
