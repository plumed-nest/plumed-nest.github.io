**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  h3/explicit/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @36 : keyword ARG is compulsory for this action
[runnervmvrwv9:09888] *** Process received signal ***
[runnervmvrwv9:09888] Signal: Aborted (6)
[runnervmvrwv9:09888] Signal code:  (-6)
[runnervmvrwv9:09888] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb7d3445330]
[runnervmvrwv9:09888] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb7d349eb2c]
[runnervmvrwv9:09888] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb7d344527e]
[runnervmvrwv9:09888] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb7d34288ff]
[runnervmvrwv9:09888] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb7d38a5ff5]
[runnervmvrwv9:09888] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb7d38bb0da]
[runnervmvrwv9:09888] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb7d38a5a55]
[runnervmvrwv9:09888] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb7d38a5a6f]
[runnervmvrwv9:09888] [ 8] plumed_master(+0x146dd)[0x55e386cbb6dd]
[runnervmvrwv9:09888] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb7d342a1ca]
[runnervmvrwv9:09888] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb7d342a28b]
[runnervmvrwv9:09888] [11] plumed_master(+0x15365)[0x55e386cbc365]
[runnervmvrwv9:09888] *** End of error message ***
</pre>
{% endraw %}
