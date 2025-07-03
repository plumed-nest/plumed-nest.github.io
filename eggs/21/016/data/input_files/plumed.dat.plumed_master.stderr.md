**Project ID:** [plumID:21.016]({{ '/' | absolute_url }}eggs/21/016/)  
Stderr for source:  input_files/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label saxs : cannot understand the following words from the input line : SCALEINT=1
[pkrvmbietmlfzoi:08547] *** Process received signal ***
[pkrvmbietmlfzoi:08547] Signal: Aborted (6)
[pkrvmbietmlfzoi:08547] Signal code:  (-6)
[pkrvmbietmlfzoi:08547] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fec9e645330]
[pkrvmbietmlfzoi:08547] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fec9e69eb2c]
[pkrvmbietmlfzoi:08547] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fec9e64527e]
[pkrvmbietmlfzoi:08547] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fec9e6288ff]
[pkrvmbietmlfzoi:08547] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fec9eaa5ff5]
[pkrvmbietmlfzoi:08547] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fec9eabb0da]
[pkrvmbietmlfzoi:08547] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fec9eaa5a55]
[pkrvmbietmlfzoi:08547] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fec9eaa5a6f]
[pkrvmbietmlfzoi:08547] [ 8] plumed_master(+0x146dd)[0x55a642b666dd]
[pkrvmbietmlfzoi:08547] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fec9e62a1ca]
[pkrvmbietmlfzoi:08547] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fec9e62a28b]
[pkrvmbietmlfzoi:08547] [11] plumed_master(+0x15365)[0x55a642b67365]
[pkrvmbietmlfzoi:08547] *** End of error message ***
</pre>
{% endraw %}
