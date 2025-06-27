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
[pkrvmbietmlfzoi:66103] *** Process received signal ***
[pkrvmbietmlfzoi:66103] Signal: Aborted (6)
[pkrvmbietmlfzoi:66103] Signal code:  (-6)
[pkrvmbietmlfzoi:66103] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd635045330]
[pkrvmbietmlfzoi:66103] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd63509eb2c]
[pkrvmbietmlfzoi:66103] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd63504527e]
[pkrvmbietmlfzoi:66103] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd6350288ff]
[pkrvmbietmlfzoi:66103] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd6354a5ff5]
[pkrvmbietmlfzoi:66103] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd6354bb0da]
[pkrvmbietmlfzoi:66103] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd6354a5a55]
[pkrvmbietmlfzoi:66103] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd6354a5a6f]
[pkrvmbietmlfzoi:66103] [ 8] plumed_master(+0x146dd)[0x555c765496dd]
[pkrvmbietmlfzoi:66103] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd63502a1ca]
[pkrvmbietmlfzoi:66103] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd63502a28b]
[pkrvmbietmlfzoi:66103] [11] plumed_master(+0x15365)[0x555c7654a365]
[pkrvmbietmlfzoi:66103] *** End of error message ***
</pre>
{% endraw %}
