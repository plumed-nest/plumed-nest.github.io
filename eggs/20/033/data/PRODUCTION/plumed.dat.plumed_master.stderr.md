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
[pkrvmbietmlfzoi:69486] *** Process received signal ***
[pkrvmbietmlfzoi:69486] Signal: Aborted (6)
[pkrvmbietmlfzoi:69486] Signal code:  (-6)
[pkrvmbietmlfzoi:69486] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0e9b045330]
[pkrvmbietmlfzoi:69486] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0e9b09eb2c]
[pkrvmbietmlfzoi:69486] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0e9b04527e]
[pkrvmbietmlfzoi:69486] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0e9b0288ff]
[pkrvmbietmlfzoi:69486] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0e9b4a5ff5]
[pkrvmbietmlfzoi:69486] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0e9b4bb0da]
[pkrvmbietmlfzoi:69486] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0e9b4a5a55]
[pkrvmbietmlfzoi:69486] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0e9b4a5a6f]
[pkrvmbietmlfzoi:69486] [ 8] plumed_master(+0x146dd)[0x5566729cb6dd]
[pkrvmbietmlfzoi:69486] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0e9b02a1ca]
[pkrvmbietmlfzoi:69486] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0e9b02a28b]
[pkrvmbietmlfzoi:69486] [11] plumed_master(+0x15365)[0x5566729cc365]
[pkrvmbietmlfzoi:69486] *** End of error message ***
</pre>
{% endraw %}
