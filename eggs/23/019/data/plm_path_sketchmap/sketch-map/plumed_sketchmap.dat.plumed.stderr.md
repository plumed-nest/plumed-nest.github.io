**Project ID:** [plumID:23.019]({{ '/' | absolute_url }}eggs/23/019/)  
Stderr for source:  plm_path_sketchmap/sketch-map/plumed_sketchmap.dat   
Download: [zipped raw stdout](plumed_sketchmap.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_sketchmap.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action VSTACK with label mat : no arguments were specificed
[pkrvmbietmlfzoi:63654] *** Process received signal ***
[pkrvmbietmlfzoi:63654] Signal: Aborted (6)
[pkrvmbietmlfzoi:63654] Signal code:  (-6)
[pkrvmbietmlfzoi:63654] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb03aa45330]
[pkrvmbietmlfzoi:63654] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb03aa9eb2c]
[pkrvmbietmlfzoi:63654] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb03aa4527e]
[pkrvmbietmlfzoi:63654] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb03aa288ff]
[pkrvmbietmlfzoi:63654] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb03aea5ff5]
[pkrvmbietmlfzoi:63654] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb03aebb0da]
[pkrvmbietmlfzoi:63654] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb03aea5a55]
[pkrvmbietmlfzoi:63654] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb03aea5a6f]
[pkrvmbietmlfzoi:63654] [ 8] plumed(+0x146dd)[0x561e9d1386dd]
[pkrvmbietmlfzoi:63654] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb03aa2a1ca]
[pkrvmbietmlfzoi:63654] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb03aa2a28b]
[pkrvmbietmlfzoi:63654] [11] plumed(+0x15365)[0x561e9d139365]
[pkrvmbietmlfzoi:63654] *** End of error message ***
</pre>
{% endraw %}
