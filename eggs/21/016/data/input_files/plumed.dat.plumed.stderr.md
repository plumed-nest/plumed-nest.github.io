**Project ID:** [plumID:21.016]({{ '/' | absolute_url }}eggs/21/016/)  
Stderr for source:  input_files/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label saxs : cannot understand the following words from the input line : SCALEINT=1
[pkrvmbietmlfzoi:66087] *** Process received signal ***
[pkrvmbietmlfzoi:66087] Signal: Aborted (6)
[pkrvmbietmlfzoi:66087] Signal code:  (-6)
[pkrvmbietmlfzoi:66087] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7e47045330]
[pkrvmbietmlfzoi:66087] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7e4709eb2c]
[pkrvmbietmlfzoi:66087] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7e4704527e]
[pkrvmbietmlfzoi:66087] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7e470288ff]
[pkrvmbietmlfzoi:66087] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7e474a5ff5]
[pkrvmbietmlfzoi:66087] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7e474bb0da]
[pkrvmbietmlfzoi:66087] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7e474a5a55]
[pkrvmbietmlfzoi:66087] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7e474a5a6f]
[pkrvmbietmlfzoi:66087] [ 8] plumed(+0x146dd)[0x561e3bc036dd]
[pkrvmbietmlfzoi:66087] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7e4702a1ca]
[pkrvmbietmlfzoi:66087] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7e4702a28b]
[pkrvmbietmlfzoi:66087] [11] plumed(+0x15365)[0x561e3bc04365]
[pkrvmbietmlfzoi:66087] *** End of error message ***
</pre>
{% endraw %}
