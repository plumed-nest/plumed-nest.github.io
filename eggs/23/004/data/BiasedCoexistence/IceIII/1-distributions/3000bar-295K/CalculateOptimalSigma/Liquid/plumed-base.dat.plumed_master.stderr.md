**Project ID:** [plumID:23.004]({{ '/' | absolute_url }}eggs/23/004/)  
Stderr for source:  BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/Liquid/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @87 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:64547] *** Process received signal ***
[pkrvmbietmlfzoi:64547] Signal: Aborted (6)
[pkrvmbietmlfzoi:64547] Signal code:  (-6)
[pkrvmbietmlfzoi:64547] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa310045330]
[pkrvmbietmlfzoi:64547] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa31009eb2c]
[pkrvmbietmlfzoi:64547] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa31004527e]
[pkrvmbietmlfzoi:64547] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa3100288ff]
[pkrvmbietmlfzoi:64547] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa3104a5ff5]
[pkrvmbietmlfzoi:64547] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa3104bb0da]
[pkrvmbietmlfzoi:64547] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa3104a5a55]
[pkrvmbietmlfzoi:64547] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa3104a5a6f]
[pkrvmbietmlfzoi:64547] [ 8] plumed_master(+0x146dd)[0x55913030b6dd]
[pkrvmbietmlfzoi:64547] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa31002a1ca]
[pkrvmbietmlfzoi:64547] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa31002a28b]
[pkrvmbietmlfzoi:64547] [11] plumed_master(+0x15365)[0x55913030c365]
[pkrvmbietmlfzoi:64547] *** End of error message ***
</pre>
{% endraw %}
