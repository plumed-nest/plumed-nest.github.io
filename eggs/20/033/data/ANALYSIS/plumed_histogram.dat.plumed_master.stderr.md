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
[runnervmi13qx:36215] *** Process received signal ***
[runnervmi13qx:36215] Signal: Aborted (6)
[runnervmi13qx:36215] Signal code:  (-6)
[runnervmi13qx:36215] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7787c45330]
[runnervmi13qx:36215] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7787c9eb2c]
[runnervmi13qx:36215] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7787c4527e]
[runnervmi13qx:36215] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7787c288ff]
[runnervmi13qx:36215] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f77880a5ff5]
[runnervmi13qx:36215] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f77880bb0da]
[runnervmi13qx:36215] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f77880a5a55]
[runnervmi13qx:36215] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f77880a5a6f]
[runnervmi13qx:36215] [ 8] plumed_master(+0x146dd)[0x55d7ec5ad6dd]
[runnervmi13qx:36215] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7787c2a1ca]
[runnervmi13qx:36215] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7787c2a28b]
[runnervmi13qx:36215] [11] plumed_master(+0x15365)[0x55d7ec5ae365]
[runnervmi13qx:36215] *** End of error message ***
</pre>
{% endraw %}
