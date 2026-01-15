**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  ohco2/asymm-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @24 : keyword ARG is compulsory for this action
[runnervmi13qx:37757] *** Process received signal ***
[runnervmi13qx:37757] Signal: Aborted (6)
[runnervmi13qx:37757] Signal code:  (-6)
[runnervmi13qx:37757] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9d19e45330]
[runnervmi13qx:37757] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9d19e9eb2c]
[runnervmi13qx:37757] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9d19e4527e]
[runnervmi13qx:37757] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9d19e288ff]
[runnervmi13qx:37757] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9d1a2a5ff5]
[runnervmi13qx:37757] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9d1a2bb0da]
[runnervmi13qx:37757] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9d1a2a5a55]
[runnervmi13qx:37757] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9d1a2a5a6f]
[runnervmi13qx:37757] [ 8] plumed_master(+0x146dd)[0x5588e97676dd]
[runnervmi13qx:37757] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9d19e2a1ca]
[runnervmi13qx:37757] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9d19e2a28b]
[runnervmi13qx:37757] [11] plumed_master(+0x15365)[0x5588e9768365]
[runnervmi13qx:37757] *** End of error message ***
</pre>
{% endraw %}
