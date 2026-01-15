**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  5dro/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @20 : keyword ARG is compulsory for this action
[runnervmi13qx:33173] *** Process received signal ***
[runnervmi13qx:33173] Signal: Aborted (6)
[runnervmi13qx:33173] Signal code:  (-6)
[runnervmi13qx:33173] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f46a5045330]
[runnervmi13qx:33173] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f46a509eb2c]
[runnervmi13qx:33173] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f46a504527e]
[runnervmi13qx:33173] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f46a50288ff]
[runnervmi13qx:33173] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f46a54a5ff5]
[runnervmi13qx:33173] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f46a54bb0da]
[runnervmi13qx:33173] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f46a54a5a55]
[runnervmi13qx:33173] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f46a54a5a6f]
[runnervmi13qx:33173] [ 8] plumed_master(+0x146dd)[0x55eebeb836dd]
[runnervmi13qx:33173] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f46a502a1ca]
[runnervmi13qx:33173] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f46a502a28b]
[runnervmi13qx:33173] [11] plumed_master(+0x15365)[0x55eebeb84365]
[runnervmi13qx:33173] *** End of error message ***
</pre>
{% endraw %}
