**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  clch3cl/ch-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @25 : keyword ARG is compulsory for this action
[runnervmvrwv9:09798] *** Process received signal ***
[runnervmvrwv9:09798] Signal: Aborted (6)
[runnervmvrwv9:09798] Signal code:  (-6)
[runnervmvrwv9:09798] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7407a45330]
[runnervmvrwv9:09798] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7407a9eb2c]
[runnervmvrwv9:09798] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7407a4527e]
[runnervmvrwv9:09798] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7407a288ff]
[runnervmvrwv9:09798] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7407ea5ff5]
[runnervmvrwv9:09798] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7407ebb0da]
[runnervmvrwv9:09798] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7407ea5a55]
[runnervmvrwv9:09798] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7407ea5a6f]
[runnervmvrwv9:09798] [ 8] plumed_master(+0x146dd)[0x555cc2f956dd]
[runnervmvrwv9:09798] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7407a2a1ca]
[runnervmvrwv9:09798] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7407a2a28b]
[runnervmvrwv9:09798] [11] plumed_master(+0x15365)[0x555cc2f96365]
[runnervmvrwv9:09798] *** End of error message ***
</pre>
{% endraw %}
