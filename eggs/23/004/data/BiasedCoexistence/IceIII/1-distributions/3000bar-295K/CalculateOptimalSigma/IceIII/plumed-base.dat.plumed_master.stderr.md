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
[pkrvmbietmlfzoi:07365] *** Process received signal ***
[pkrvmbietmlfzoi:07365] Signal: Aborted (6)
[pkrvmbietmlfzoi:07365] Signal code:  (-6)
[pkrvmbietmlfzoi:07365] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6402e45330]
[pkrvmbietmlfzoi:07365] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6402e9eb2c]
[pkrvmbietmlfzoi:07365] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6402e4527e]
[pkrvmbietmlfzoi:07365] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6402e288ff]
[pkrvmbietmlfzoi:07365] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f64032a5ff5]
[pkrvmbietmlfzoi:07365] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f64032bb0da]
[pkrvmbietmlfzoi:07365] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f64032a5a55]
[pkrvmbietmlfzoi:07365] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f64032a5a6f]
[pkrvmbietmlfzoi:07365] [ 8] plumed_master(+0x146dd)[0x55d03d5a96dd]
[pkrvmbietmlfzoi:07365] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6402e2a1ca]
[pkrvmbietmlfzoi:07365] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6402e2a28b]
[pkrvmbietmlfzoi:07365] [11] plumed_master(+0x15365)[0x55d03d5aa365]
[pkrvmbietmlfzoi:07365] *** End of error message ***
</pre>
{% endraw %}
