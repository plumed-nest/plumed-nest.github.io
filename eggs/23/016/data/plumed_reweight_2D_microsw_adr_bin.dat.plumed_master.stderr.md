**Project ID:** [plumID:23.016]({{ '/' | absolute_url }}eggs/23/016/)  
Stderr for source:  plumed_reweight_2D_microsw_adr_bin.dat   
Download: [zipped raw stdout](plumed_reweight_2D_microsw_adr_bin.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_2D_microsw_adr_bin.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @60 : keyword ARG is compulsory for this action
[runnervmmtnos:33444] *** Process received signal ***
[runnervmmtnos:33444] Signal: Aborted (6)
[runnervmmtnos:33444] Signal code:  (-6)
[runnervmmtnos:33444] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd002e45330]
[runnervmmtnos:33444] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd002e9eb2c]
[runnervmmtnos:33444] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd002e4527e]
[runnervmmtnos:33444] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd002e288ff]
[runnervmmtnos:33444] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd0032a5ff5]
[runnervmmtnos:33444] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd0032bb0da]
[runnervmmtnos:33444] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd0032a5a55]
[runnervmmtnos:33444] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd0032a5a6f]
[runnervmmtnos:33444] [ 8] plumed_master(+0x146dd)[0x55f4f4f016dd]
[runnervmmtnos:33444] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd002e2a1ca]
[runnervmmtnos:33444] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd002e2a28b]
[runnervmmtnos:33444] [11] plumed_master(+0x15365)[0x55f4f4f02365]
[runnervmmtnos:33444] *** End of error message ***
</pre>
{% endraw %}
