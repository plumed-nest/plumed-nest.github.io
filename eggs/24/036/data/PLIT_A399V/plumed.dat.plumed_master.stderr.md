**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT_A399V/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @24 : keyword ARG is compulsory for this action
[runnervmi13qx:33496] *** Process received signal ***
[runnervmi13qx:33496] Signal: Aborted (6)
[runnervmi13qx:33496] Signal code:  (-6)
[runnervmi13qx:33496] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe454a45330]
[runnervmi13qx:33496] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe454a9eb2c]
[runnervmi13qx:33496] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe454a4527e]
[runnervmi13qx:33496] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe454a288ff]
[runnervmi13qx:33496] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe454ea5ff5]
[runnervmi13qx:33496] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe454ebb0da]
[runnervmi13qx:33496] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe454ea5a55]
[runnervmi13qx:33496] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe454ea5a6f]
[runnervmi13qx:33496] [ 8] plumed_master(+0x146dd)[0x561e557406dd]
[runnervmi13qx:33496] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe454a2a1ca]
[runnervmi13qx:33496] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe454a2a28b]
[runnervmi13qx:33496] [11] plumed_master(+0x15365)[0x561e55741365]
[runnervmi13qx:33496] *** End of error message ***
</pre>
{% endraw %}
