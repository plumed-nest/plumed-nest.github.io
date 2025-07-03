**Project ID:** [plumID:23.004]({{ '/' | absolute_url }}eggs/23/004/)  
Stderr for source:  BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/IceIII/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @87 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:07405] *** Process received signal ***
[pkrvmbietmlfzoi:07405] Signal: Aborted (6)
[pkrvmbietmlfzoi:07405] Signal code:  (-6)
[pkrvmbietmlfzoi:07405] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f767e845330]
[pkrvmbietmlfzoi:07405] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f767e89eb2c]
[pkrvmbietmlfzoi:07405] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f767e84527e]
[pkrvmbietmlfzoi:07405] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f767e8288ff]
[pkrvmbietmlfzoi:07405] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f767eca5ff5]
[pkrvmbietmlfzoi:07405] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f767ecbb0da]
[pkrvmbietmlfzoi:07405] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f767eca5a55]
[pkrvmbietmlfzoi:07405] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f767eca5a6f]
[pkrvmbietmlfzoi:07405] [ 8] plumed_master(+0x146dd)[0x564adcb356dd]
[pkrvmbietmlfzoi:07405] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f767e82a1ca]
[pkrvmbietmlfzoi:07405] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f767e82a28b]
[pkrvmbietmlfzoi:07405] [11] plumed_master(+0x15365)[0x564adcb36365]
[pkrvmbietmlfzoi:07405] *** End of error message ***
</pre>
{% endraw %}
