**Project ID:** [plumID:25.029]({{ '/' | absolute_url }}eggs/25/029/)  
Stderr for source:  ./crys/4-reweight_crys.dat   
Download: [zipped raw stdout](4-reweight_crys.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](4-reweight_crys.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @46 : keyword ARG is compulsory for this action
[runnervmi13qx:31865] *** Process received signal ***
[runnervmi13qx:31865] Signal: Aborted (6)
[runnervmi13qx:31865] Signal code:  (-6)
[runnervmi13qx:31865] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f13d6c45330]
[runnervmi13qx:31865] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f13d6c9eb2c]
[runnervmi13qx:31865] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f13d6c4527e]
[runnervmi13qx:31865] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f13d6c288ff]
[runnervmi13qx:31865] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f13d70a5ff5]
[runnervmi13qx:31865] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f13d70bb0da]
[runnervmi13qx:31865] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f13d70a5a55]
[runnervmi13qx:31865] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f13d70a5a6f]
[runnervmi13qx:31865] [ 8] plumed_master(+0x146dd)[0x5618711036dd]
[runnervmi13qx:31865] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f13d6c2a1ca]
[runnervmi13qx:31865] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f13d6c2a28b]
[runnervmi13qx:31865] [11] plumed_master(+0x15365)[0x561871104365]
[runnervmi13qx:31865] *** End of error message ***
</pre>
{% endraw %}
