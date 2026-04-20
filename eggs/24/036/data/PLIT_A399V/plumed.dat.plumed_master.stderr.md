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
[runnervmeorf1:05129] *** Process received signal ***
[runnervmeorf1:05129] Signal: Aborted (6)
[runnervmeorf1:05129] Signal code:  (-6)
[runnervmeorf1:05129] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5662a45330]
[runnervmeorf1:05129] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5662a9eb2c]
[runnervmeorf1:05129] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5662a4527e]
[runnervmeorf1:05129] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5662a288ff]
[runnervmeorf1:05129] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5662ea5ff5]
[runnervmeorf1:05129] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5662ebb0da]
[runnervmeorf1:05129] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5662ea5a55]
[runnervmeorf1:05129] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5662ea5a6f]
[runnervmeorf1:05129] [ 8] plumed_master(+0x146dd)[0x55e4d24276dd]
[runnervmeorf1:05129] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5662a2a1ca]
[runnervmeorf1:05129] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5662a2a28b]
[runnervmeorf1:05129] [11] plumed_master(+0x15365)[0x55e4d2428365]
[runnervmeorf1:05129] *** End of error message ***
</pre>
{% endraw %}
