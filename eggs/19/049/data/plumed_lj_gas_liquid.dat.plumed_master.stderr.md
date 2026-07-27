**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_lj_gas_liquid.dat   
Download: [zipped raw stdout](plumed_lj_gas_liquid.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_lj_gas_liquid.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DFSCLUSTERING with label dfs : keyword ARG is compulsory for this action
[runnervmvrwv9:10175] *** Process received signal ***
[runnervmvrwv9:10175] Signal: Aborted (6)
[runnervmvrwv9:10175] Signal code:  (-6)
[runnervmvrwv9:10175] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc43ae45330]
[runnervmvrwv9:10175] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc43ae9eb2c]
[runnervmvrwv9:10175] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc43ae4527e]
[runnervmvrwv9:10175] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc43ae288ff]
[runnervmvrwv9:10175] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc43b2a5ff5]
[runnervmvrwv9:10175] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc43b2bb0da]
[runnervmvrwv9:10175] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc43b2a5a55]
[runnervmvrwv9:10175] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc43b2a5a6f]
[runnervmvrwv9:10175] [ 8] plumed_master(+0x146dd)[0x55824eeff6dd]
[runnervmvrwv9:10175] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc43ae2a1ca]
[runnervmvrwv9:10175] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc43ae2a28b]
[runnervmvrwv9:10175] [11] plumed_master(+0x15365)[0x55824ef00365]
[runnervmvrwv9:10175] *** End of error message ***
</pre>
{% endraw %}
