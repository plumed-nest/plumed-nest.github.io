**Project ID:** [plumID:23.004]({{ '/' | absolute_url }}eggs/23/004/)  
Stderr for source:  BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/IceIII/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @87 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:64470] *** Process received signal ***
[pkrvmbietmlfzoi:64470] Signal: Aborted (6)
[pkrvmbietmlfzoi:64470] Signal code:  (-6)
[pkrvmbietmlfzoi:64470] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efdd0445330]
[pkrvmbietmlfzoi:64470] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efdd049eb2c]
[pkrvmbietmlfzoi:64470] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efdd044527e]
[pkrvmbietmlfzoi:64470] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efdd04288ff]
[pkrvmbietmlfzoi:64470] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efdd08a5ff5]
[pkrvmbietmlfzoi:64470] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efdd08bb0da]
[pkrvmbietmlfzoi:64470] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efdd08a5a55]
[pkrvmbietmlfzoi:64470] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efdd08a5a6f]
[pkrvmbietmlfzoi:64470] [ 8] plumed_master(+0x146dd)[0x5616319ef6dd]
[pkrvmbietmlfzoi:64470] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efdd042a1ca]
[pkrvmbietmlfzoi:64470] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efdd042a28b]
[pkrvmbietmlfzoi:64470] [11] plumed_master(+0x15365)[0x5616319f0365]
[pkrvmbietmlfzoi:64470] *** End of error message ***
</pre>
{% endraw %}
