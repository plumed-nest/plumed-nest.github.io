**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  h3/explicit/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @36 : keyword ARG is compulsory for this action
[runnervmi13qx:38176] *** Process received signal ***
[runnervmi13qx:38176] Signal: Aborted (6)
[runnervmi13qx:38176] Signal code:  (-6)
[runnervmi13qx:38176] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8418c45330]
[runnervmi13qx:38176] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8418c9eb2c]
[runnervmi13qx:38176] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8418c4527e]
[runnervmi13qx:38176] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8418c288ff]
[runnervmi13qx:38176] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f84190a5ff5]
[runnervmi13qx:38176] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f84190bb0da]
[runnervmi13qx:38176] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f84190a5a55]
[runnervmi13qx:38176] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f84190a5a6f]
[runnervmi13qx:38176] [ 8] plumed_master(+0x146dd)[0x55ea9aa906dd]
[runnervmi13qx:38176] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8418c2a1ca]
[runnervmi13qx:38176] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8418c2a28b]
[runnervmi13qx:38176] [11] plumed_master(+0x15365)[0x55ea9aa91365]
[runnervmi13qx:38176] *** End of error message ***
</pre>
{% endraw %}
