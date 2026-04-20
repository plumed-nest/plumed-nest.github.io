**Project ID:** [plumID:20.033]({{ '/' | absolute_url }}eggs/20/033/)  
Stderr for source:  ANALYSIS/plumed_histogram.dat   
Download: [zipped raw stdout](plumed_histogram.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_histogram.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @20 : keyword ARG is compulsory for this action
[runnervmeorf1:09147] *** Process received signal ***
[runnervmeorf1:09147] Signal: Aborted (6)
[runnervmeorf1:09147] Signal code:  (-6)
[runnervmeorf1:09147] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6988245330]
[runnervmeorf1:09147] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f698829eb2c]
[runnervmeorf1:09147] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f698824527e]
[runnervmeorf1:09147] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f69882288ff]
[runnervmeorf1:09147] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f69886a5ff5]
[runnervmeorf1:09147] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f69886bb0da]
[runnervmeorf1:09147] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f69886a5a55]
[runnervmeorf1:09147] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f69886a5a6f]
[runnervmeorf1:09147] [ 8] plumed_master(+0x146dd)[0x557b74f186dd]
[runnervmeorf1:09147] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f698822a1ca]
[runnervmeorf1:09147] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f698822a28b]
[runnervmeorf1:09147] [11] plumed_master(+0x15365)[0x557b74f19365]
[runnervmeorf1:09147] *** End of error message ***
</pre>
{% endraw %}
