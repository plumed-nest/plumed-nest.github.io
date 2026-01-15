**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT/plumed_h1h2.dat   
Download: [zipped raw stdout](plumed_h1h2.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_h1h2.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @38 : keyword ARG is compulsory for this action
[runnervmi13qx:33354] *** Process received signal ***
[runnervmi13qx:33354] Signal: Aborted (6)
[runnervmi13qx:33354] Signal code:  (-6)
[runnervmi13qx:33354] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efc4bc45330]
[runnervmi13qx:33354] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efc4bc9eb2c]
[runnervmi13qx:33354] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efc4bc4527e]
[runnervmi13qx:33354] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efc4bc288ff]
[runnervmi13qx:33354] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efc4c0a5ff5]
[runnervmi13qx:33354] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efc4c0bb0da]
[runnervmi13qx:33354] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efc4c0a5a55]
[runnervmi13qx:33354] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efc4c0a5a6f]
[runnervmi13qx:33354] [ 8] plumed_master(+0x146dd)[0x560a8339c6dd]
[runnervmi13qx:33354] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efc4bc2a1ca]
[runnervmi13qx:33354] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efc4bc2a28b]
[runnervmi13qx:33354] [11] plumed_master(+0x15365)[0x560a8339d365]
[runnervmi13qx:33354] *** End of error message ***
</pre>
{% endraw %}
