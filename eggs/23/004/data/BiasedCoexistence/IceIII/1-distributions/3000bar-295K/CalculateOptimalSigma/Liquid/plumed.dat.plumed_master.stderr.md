**Project ID:** [plumID:23.004]({{ '/' | absolute_url }}eggs/23/004/)  
Stderr for source:  BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/Liquid/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @87 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:07483] *** Process received signal ***
[pkrvmbietmlfzoi:07483] Signal: Aborted (6)
[pkrvmbietmlfzoi:07483] Signal code:  (-6)
[pkrvmbietmlfzoi:07483] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f07dd245330]
[pkrvmbietmlfzoi:07483] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f07dd29eb2c]
[pkrvmbietmlfzoi:07483] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f07dd24527e]
[pkrvmbietmlfzoi:07483] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f07dd2288ff]
[pkrvmbietmlfzoi:07483] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f07dd6a5ff5]
[pkrvmbietmlfzoi:07483] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f07dd6bb0da]
[pkrvmbietmlfzoi:07483] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f07dd6a5a55]
[pkrvmbietmlfzoi:07483] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f07dd6a5a6f]
[pkrvmbietmlfzoi:07483] [ 8] plumed_master(+0x146dd)[0x555bf0a4a6dd]
[pkrvmbietmlfzoi:07483] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f07dd22a1ca]
[pkrvmbietmlfzoi:07483] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f07dd22a28b]
[pkrvmbietmlfzoi:07483] [11] plumed_master(+0x15365)[0x555bf0a4b365]
[pkrvmbietmlfzoi:07483] *** End of error message ***
</pre>
{% endraw %}
