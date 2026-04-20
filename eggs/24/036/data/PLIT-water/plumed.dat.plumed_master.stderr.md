**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT-water/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @36 : keyword ARG is compulsory for this action
[runnervmeorf1:05091] *** Process received signal ***
[runnervmeorf1:05091] Signal: Aborted (6)
[runnervmeorf1:05091] Signal code:  (-6)
[runnervmeorf1:05091] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcd8e245330]
[runnervmeorf1:05091] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcd8e29eb2c]
[runnervmeorf1:05091] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcd8e24527e]
[runnervmeorf1:05091] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcd8e2288ff]
[runnervmeorf1:05091] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcd8e6a5ff5]
[runnervmeorf1:05091] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcd8e6bb0da]
[runnervmeorf1:05091] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcd8e6a5a55]
[runnervmeorf1:05091] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcd8e6a5a6f]
[runnervmeorf1:05091] [ 8] plumed_master(+0x146dd)[0x5653f2c006dd]
[runnervmeorf1:05091] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcd8e22a1ca]
[runnervmeorf1:05091] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcd8e22a28b]
[runnervmeorf1:05091] [11] plumed_master(+0x15365)[0x5653f2c01365]
[runnervmeorf1:05091] *** End of error message ***
</pre>
{% endraw %}
