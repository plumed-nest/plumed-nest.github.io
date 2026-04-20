**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  h3/explicit/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @36 : keyword ARG is compulsory for this action
[runnervmeorf1:11259] *** Process received signal ***
[runnervmeorf1:11259] Signal: Aborted (6)
[runnervmeorf1:11259] Signal code:  (-6)
[runnervmeorf1:11259] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1302845330]
[runnervmeorf1:11259] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f130289eb2c]
[runnervmeorf1:11259] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f130284527e]
[runnervmeorf1:11259] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f13028288ff]
[runnervmeorf1:11259] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1302ca5ff5]
[runnervmeorf1:11259] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1302cbb0da]
[runnervmeorf1:11259] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1302ca5a55]
[runnervmeorf1:11259] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1302ca5a6f]
[runnervmeorf1:11259] [ 8] plumed_master(+0x146dd)[0x55e0c7be66dd]
[runnervmeorf1:11259] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f130282a1ca]
[runnervmeorf1:11259] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f130282a28b]
[runnervmeorf1:11259] [11] plumed_master(+0x15365)[0x55e0c7be7365]
[runnervmeorf1:11259] *** End of error message ***
</pre>
{% endraw %}
