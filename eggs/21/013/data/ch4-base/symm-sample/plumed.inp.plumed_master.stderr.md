**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-base/symm-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @34 : keyword ARG is compulsory for this action
[runnervmi13qx:38488] *** Process received signal ***
[runnervmi13qx:38488] Signal: Aborted (6)
[runnervmi13qx:38488] Signal code:  (-6)
[runnervmi13qx:38488] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd771045330]
[runnervmi13qx:38488] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd77109eb2c]
[runnervmi13qx:38488] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd77104527e]
[runnervmi13qx:38488] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd7710288ff]
[runnervmi13qx:38488] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd7714a5ff5]
[runnervmi13qx:38488] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd7714bb0da]
[runnervmi13qx:38488] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd7714a5a55]
[runnervmi13qx:38488] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd7714a5a6f]
[runnervmi13qx:38488] [ 8] plumed_master(+0x146dd)[0x55c3de6b36dd]
[runnervmi13qx:38488] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd77102a1ca]
[runnervmi13qx:38488] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd77102a28b]
[runnervmi13qx:38488] [11] plumed_master(+0x15365)[0x55c3de6b4365]
[runnervmi13qx:38488] *** End of error message ***
</pre>
{% endraw %}
