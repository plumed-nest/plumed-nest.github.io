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
[pkrvmbietmlfzoi:08531] *** Process received signal ***
[pkrvmbietmlfzoi:08531] Signal: Aborted (6)
[pkrvmbietmlfzoi:08531] Signal code:  (-6)
[pkrvmbietmlfzoi:08531] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdd1a245330]
[pkrvmbietmlfzoi:08531] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdd1a29eb2c]
[pkrvmbietmlfzoi:08531] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdd1a24527e]
[pkrvmbietmlfzoi:08531] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdd1a2288ff]
[pkrvmbietmlfzoi:08531] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdd1a6a5ff5]
[pkrvmbietmlfzoi:08531] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdd1a6bb0da]
[pkrvmbietmlfzoi:08531] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdd1a6a5a55]
[pkrvmbietmlfzoi:08531] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdd1a6a5a6f]
[pkrvmbietmlfzoi:08531] [ 8] plumed(+0x146dd)[0x55d43c1e46dd]
[pkrvmbietmlfzoi:08531] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdd1a22a1ca]
[pkrvmbietmlfzoi:08531] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdd1a22a28b]
[pkrvmbietmlfzoi:08531] [11] plumed(+0x15365)[0x55d43c1e5365]
[pkrvmbietmlfzoi:08531] *** End of error message ***
</pre>
{% endraw %}
