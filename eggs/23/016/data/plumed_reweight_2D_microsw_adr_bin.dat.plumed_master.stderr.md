**Project ID:** [plumID:23.016]({{ '/' | absolute_url }}eggs/23/016/)  
Stderr for source:  plumed_reweight_2D_microsw_adr_bin.dat   
Download: [zipped raw stdout](plumed_reweight_2D_microsw_adr_bin.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_2D_microsw_adr_bin.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @87 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:62656] *** Process received signal ***
[pkrvmbietmlfzoi:62656] Signal: Aborted (6)
[pkrvmbietmlfzoi:62656] Signal code:  (-6)
[pkrvmbietmlfzoi:62656] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1208e45330]
[pkrvmbietmlfzoi:62656] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1208e9eb2c]
[pkrvmbietmlfzoi:62656] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1208e4527e]
[pkrvmbietmlfzoi:62656] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1208e288ff]
[pkrvmbietmlfzoi:62656] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f12092a5ff5]
[pkrvmbietmlfzoi:62656] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f12092bb0da]
[pkrvmbietmlfzoi:62656] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f12092a5a55]
[pkrvmbietmlfzoi:62656] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f12092a5a6f]
[pkrvmbietmlfzoi:62656] [ 8] plumed_master(+0x146dd)[0x558d686296dd]
[pkrvmbietmlfzoi:62656] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1208e2a1ca]
[pkrvmbietmlfzoi:62656] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1208e2a28b]
[pkrvmbietmlfzoi:62656] [11] plumed_master(+0x15365)[0x558d6862a365]
[pkrvmbietmlfzoi:62656] *** End of error message ***
</pre>
{% endraw %}
