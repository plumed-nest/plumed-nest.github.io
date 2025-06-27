**Project ID:** [plumID:25.015]({{ '/' | absolute_url }}eggs/25/015/)  
Stderr for source:  PLUMED_Inputs/plumed_torsion.dat   
Download: [zipped raw stdout](plumed_torsion.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_torsion.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPATOMS with label @6 : it was not possible to interpret atom name t1_grp
[pkrvmbietmlfzoi:61871] *** Process received signal ***
[pkrvmbietmlfzoi:61871] Signal: Aborted (6)
[pkrvmbietmlfzoi:61871] Signal code:  (-6)
[pkrvmbietmlfzoi:61871] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f830b845330]
[pkrvmbietmlfzoi:61871] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f830b89eb2c]
[pkrvmbietmlfzoi:61871] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f830b84527e]
[pkrvmbietmlfzoi:61871] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f830b8288ff]
[pkrvmbietmlfzoi:61871] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f830bca5ff5]
[pkrvmbietmlfzoi:61871] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f830bcbb0da]
[pkrvmbietmlfzoi:61871] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f830bca5a55]
[pkrvmbietmlfzoi:61871] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f830bca5a6f]
[pkrvmbietmlfzoi:61871] [ 8] plumed(+0x146dd)[0x55cffd0f76dd]
[pkrvmbietmlfzoi:61871] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f830b82a1ca]
[pkrvmbietmlfzoi:61871] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f830b82a28b]
[pkrvmbietmlfzoi:61871] [11] plumed(+0x15365)[0x55cffd0f8365]
[pkrvmbietmlfzoi:61871] *** End of error message ***
</pre>
{% endraw %}
