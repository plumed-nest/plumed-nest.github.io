**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  ohco2/asymm-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @24 : keyword ARG is compulsory for this action
[runnervmvrwv9:09463] *** Process received signal ***
[runnervmvrwv9:09463] Signal: Aborted (6)
[runnervmvrwv9:09463] Signal code:  (-6)
[runnervmvrwv9:09463] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3212a45330]
[runnervmvrwv9:09463] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3212a9eb2c]
[runnervmvrwv9:09463] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3212a4527e]
[runnervmvrwv9:09463] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3212a288ff]
[runnervmvrwv9:09463] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3212ea5ff5]
[runnervmvrwv9:09463] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3212ebb0da]
[runnervmvrwv9:09463] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3212ea5a55]
[runnervmvrwv9:09463] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3212ea5a6f]
[runnervmvrwv9:09463] [ 8] plumed_master(+0x146dd)[0x563ca196a6dd]
[runnervmvrwv9:09463] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3212a2a1ca]
[runnervmvrwv9:09463] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3212a2a28b]
[runnervmvrwv9:09463] [11] plumed_master(+0x15365)[0x563ca196b365]
[runnervmvrwv9:09463] *** End of error message ***
</pre>
{% endraw %}
