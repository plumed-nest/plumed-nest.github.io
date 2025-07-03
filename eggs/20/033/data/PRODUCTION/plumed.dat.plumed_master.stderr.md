**Project ID:** [plumID:20.033]({{ '/' | absolute_url }}eggs/20/033/)  
Stderr for source:  PRODUCTION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action WHOLEMOLECULES with label @5 : cannot understand the following words from the input line : REF0=16.995,21.964,24.520, REF1=26.253,18.440,24.5030, REF2=24.616,28.069,24.203
[pkrvmbietmlfzoi:11084] *** Process received signal ***
[pkrvmbietmlfzoi:11084] Signal: Aborted (6)
[pkrvmbietmlfzoi:11084] Signal code:  (-6)
[pkrvmbietmlfzoi:11084] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa4d0045330]
[pkrvmbietmlfzoi:11084] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa4d009eb2c]
[pkrvmbietmlfzoi:11084] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa4d004527e]
[pkrvmbietmlfzoi:11084] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa4d00288ff]
[pkrvmbietmlfzoi:11084] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa4d04a5ff5]
[pkrvmbietmlfzoi:11084] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa4d04bb0da]
[pkrvmbietmlfzoi:11084] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa4d04a5a55]
[pkrvmbietmlfzoi:11084] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa4d04a5a6f]
[pkrvmbietmlfzoi:11084] [ 8] plumed_master(+0x146dd)[0x55e8b69b46dd]
[pkrvmbietmlfzoi:11084] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa4d002a1ca]
[pkrvmbietmlfzoi:11084] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa4d002a28b]
[pkrvmbietmlfzoi:11084] [11] plumed_master(+0x15365)[0x55e8b69b5365]
[pkrvmbietmlfzoi:11084] *** End of error message ***
</pre>
{% endraw %}
