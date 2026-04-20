**Project ID:** [plumID:23.004]({{ '/' | absolute_url }}eggs/23/004/)  
Stderr for source:  BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/IceIII/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @77 : keyword ARG is compulsory for this action
[runnervmeorf1:08067] *** Process received signal ***
[runnervmeorf1:08067] Signal: Aborted (6)
[runnervmeorf1:08067] Signal code:  (-6)
[runnervmeorf1:08067] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fca92e45330]
[runnervmeorf1:08067] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fca92e9eb2c]
[runnervmeorf1:08067] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fca92e4527e]
[runnervmeorf1:08067] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fca92e288ff]
[runnervmeorf1:08067] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fca932a5ff5]
[runnervmeorf1:08067] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fca932bb0da]
[runnervmeorf1:08067] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fca932a5a55]
[runnervmeorf1:08067] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fca932a5a6f]
[runnervmeorf1:08067] [ 8] plumed_master(+0x146dd)[0x5644796406dd]
[runnervmeorf1:08067] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fca92e2a1ca]
[runnervmeorf1:08067] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fca92e2a28b]
[runnervmeorf1:08067] [11] plumed_master(+0x15365)[0x564479641365]
[runnervmeorf1:08067] *** End of error message ***
</pre>
{% endraw %}
