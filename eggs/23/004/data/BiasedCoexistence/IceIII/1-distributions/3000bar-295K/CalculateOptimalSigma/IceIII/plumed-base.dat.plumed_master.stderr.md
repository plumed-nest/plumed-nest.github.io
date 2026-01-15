**Project ID:** [plumID:23.004]({{ '/' | absolute_url }}eggs/23/004/)  
Stderr for source:  BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/IceIII/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @77 : keyword ARG is compulsory for this action
[runnervmi13qx:33775] *** Process received signal ***
[runnervmi13qx:33775] Signal: Aborted (6)
[runnervmi13qx:33775] Signal code:  (-6)
[runnervmi13qx:33775] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd3cd245330]
[runnervmi13qx:33775] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd3cd29eb2c]
[runnervmi13qx:33775] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd3cd24527e]
[runnervmi13qx:33775] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd3cd2288ff]
[runnervmi13qx:33775] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd3cd6a5ff5]
[runnervmi13qx:33775] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd3cd6bb0da]
[runnervmi13qx:33775] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd3cd6a5a55]
[runnervmi13qx:33775] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd3cd6a5a6f]
[runnervmi13qx:33775] [ 8] plumed_master(+0x146dd)[0x55e0653ff6dd]
[runnervmi13qx:33775] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd3cd22a1ca]
[runnervmi13qx:33775] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd3cd22a28b]
[runnervmi13qx:33775] [11] plumed_master(+0x15365)[0x55e065400365]
[runnervmi13qx:33775] *** End of error message ***
</pre>
{% endraw %}
