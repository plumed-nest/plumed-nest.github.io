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
[pkrvm7jw40e0xgp:09725] *** Process received signal ***
[pkrvm7jw40e0xgp:09725] Signal: Aborted (6)
[pkrvm7jw40e0xgp:09725] Signal code:  (-6)
[pkrvm7jw40e0xgp:09725] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4e96245330]
[pkrvm7jw40e0xgp:09725] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4e9629eb2c]
[pkrvm7jw40e0xgp:09725] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4e9624527e]
[pkrvm7jw40e0xgp:09725] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4e962288ff]
[pkrvm7jw40e0xgp:09725] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4e966a5ff5]
[pkrvm7jw40e0xgp:09725] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4e966bb0da]
[pkrvm7jw40e0xgp:09725] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4e966a5a55]
[pkrvm7jw40e0xgp:09725] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4e966a5a6f]
[pkrvm7jw40e0xgp:09725] [ 8] plumed(+0x146dd)[0x55fd372326dd]
[pkrvm7jw40e0xgp:09725] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4e9622a1ca]
[pkrvm7jw40e0xgp:09725] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4e9622a28b]
[pkrvm7jw40e0xgp:09725] [11] plumed(+0x15365)[0x55fd37233365]
[pkrvm7jw40e0xgp:09725] *** End of error message ***
</pre>
{% endraw %}
