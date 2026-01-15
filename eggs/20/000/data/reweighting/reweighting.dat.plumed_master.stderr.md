**Project ID:** [plumID:20.000]({{ '/' | absolute_url }}eggs/20/000/)  
Stderr for source:  reweighting/reweighting.dat   
Download: [zipped raw stdout](reweighting.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweighting.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @20 : keyword ARG is compulsory for this action
[runnervmi13qx:37689] *** Process received signal ***
[runnervmi13qx:37689] Signal: Aborted (6)
[runnervmi13qx:37689] Signal code:  (-6)
[runnervmi13qx:37689] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd4f4e45330]
[runnervmi13qx:37689] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd4f4e9eb2c]
[runnervmi13qx:37689] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd4f4e4527e]
[runnervmi13qx:37689] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd4f4e288ff]
[runnervmi13qx:37689] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd4f52a5ff5]
[runnervmi13qx:37689] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd4f52bb0da]
[runnervmi13qx:37689] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd4f52a5a55]
[runnervmi13qx:37689] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd4f52a5a6f]
[runnervmi13qx:37689] [ 8] plumed_master(+0x146dd)[0x55c892c286dd]
[runnervmi13qx:37689] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd4f4e2a1ca]
[runnervmi13qx:37689] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd4f4e2a28b]
[runnervmi13qx:37689] [11] plumed_master(+0x15365)[0x55c892c29365]
[runnervmi13qx:37689] *** End of error message ***
</pre>
{% endraw %}
