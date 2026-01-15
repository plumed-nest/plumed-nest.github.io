**Project ID:** [plumID:23.004]({{ '/' | absolute_url }}eggs/23/004/)  
Stderr for source:  BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/Liquid/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @77 : keyword ARG is compulsory for this action
[runnervmi13qx:33856] *** Process received signal ***
[runnervmi13qx:33856] Signal: Aborted (6)
[runnervmi13qx:33856] Signal code:  (-6)
[runnervmi13qx:33856] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f290f845330]
[runnervmi13qx:33856] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f290f89eb2c]
[runnervmi13qx:33856] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f290f84527e]
[runnervmi13qx:33856] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f290f8288ff]
[runnervmi13qx:33856] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f290fca5ff5]
[runnervmi13qx:33856] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f290fcbb0da]
[runnervmi13qx:33856] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f290fca5a55]
[runnervmi13qx:33856] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f290fca5a6f]
[runnervmi13qx:33856] [ 8] plumed_master(+0x146dd)[0x55a196a806dd]
[runnervmi13qx:33856] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f290f82a1ca]
[runnervmi13qx:33856] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f290f82a28b]
[runnervmi13qx:33856] [11] plumed_master(+0x15365)[0x55a196a81365]
[runnervmi13qx:33856] *** End of error message ***
</pre>
{% endraw %}
