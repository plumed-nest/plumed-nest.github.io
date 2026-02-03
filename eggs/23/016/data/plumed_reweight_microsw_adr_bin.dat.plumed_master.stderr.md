**Project ID:** [plumID:23.016]({{ '/' | absolute_url }}eggs/23/016/)  
Stderr for source:  plumed_reweight_microsw_adr_bin.dat   
Download: [zipped raw stdout](plumed_reweight_microsw_adr_bin.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_microsw_adr_bin.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @107 : keyword ARG is compulsory for this action
[runnervmkj6or:09261] *** Process received signal ***
[runnervmkj6or:09261] Signal: Aborted (6)
[runnervmkj6or:09261] Signal code:  (-6)
[runnervmkj6or:09261] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f23f2445330]
[runnervmkj6or:09261] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f23f249eb2c]
[runnervmkj6or:09261] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f23f244527e]
[runnervmkj6or:09261] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f23f24288ff]
[runnervmkj6or:09261] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f23f28a5ff5]
[runnervmkj6or:09261] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f23f28bb0da]
[runnervmkj6or:09261] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f23f28a5a55]
[runnervmkj6or:09261] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f23f28a5a6f]
[runnervmkj6or:09261] [ 8] plumed_master(+0x146dd)[0x55d83676b6dd]
[runnervmkj6or:09261] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f23f242a1ca]
[runnervmkj6or:09261] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f23f242a28b]
[runnervmkj6or:09261] [11] plumed_master(+0x15365)[0x55d83676c365]
[runnervmkj6or:09261] *** End of error message ***
</pre>
{% endraw %}
