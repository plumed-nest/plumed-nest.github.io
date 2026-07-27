**Project ID:** [plumID:20.033]({{ '/' | absolute_url }}eggs/20/033/)  
Stderr for source:  ANALYSIS/plumed_histogram.dat   
Download: [zipped raw stdout](plumed_histogram.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_histogram.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @20 : keyword ARG is compulsory for this action
[runnervmvrwv9:09278] *** Process received signal ***
[runnervmvrwv9:09278] Signal: Aborted (6)
[runnervmvrwv9:09278] Signal code:  (-6)
[runnervmvrwv9:09278] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff9b5e45330]
[runnervmvrwv9:09278] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff9b5e9eb2c]
[runnervmvrwv9:09278] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff9b5e4527e]
[runnervmvrwv9:09278] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff9b5e288ff]
[runnervmvrwv9:09278] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff9b62a5ff5]
[runnervmvrwv9:09278] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff9b62bb0da]
[runnervmvrwv9:09278] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff9b62a5a55]
[runnervmvrwv9:09278] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff9b62a5a6f]
[runnervmvrwv9:09278] [ 8] plumed_master(+0x146dd)[0x55805cf866dd]
[runnervmvrwv9:09278] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff9b5e2a1ca]
[runnervmvrwv9:09278] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff9b5e2a28b]
[runnervmvrwv9:09278] [11] plumed_master(+0x15365)[0x55805cf87365]
[runnervmvrwv9:09278] *** End of error message ***
</pre>
{% endraw %}
