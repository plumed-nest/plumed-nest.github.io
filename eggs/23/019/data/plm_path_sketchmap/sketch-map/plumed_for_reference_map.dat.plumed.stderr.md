**Project ID:** [plumID:23.019]({{ '/' | absolute_url }}eggs/23/019/)  
Stderr for source:  plm_path_sketchmap/sketch-map/plumed_for_reference_map.dat   
Download: [zipped raw stdout](plumed_for_reference_map.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_for_reference_map.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action VSTACK with label mat : no arguments were specificed
[fv-az1341-704:62020] *** Process received signal ***
[fv-az1341-704:62020] Signal: Aborted (6)
[fv-az1341-704:62020] Signal code:  (-6)
[fv-az1341-704:62020] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb710045330]
[fv-az1341-704:62020] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb71009eb2c]
[fv-az1341-704:62020] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb71004527e]
[fv-az1341-704:62020] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb7100288ff]
[fv-az1341-704:62020] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb7104a5ff5]
[fv-az1341-704:62020] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb7104bb0da]
[fv-az1341-704:62020] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb7104a5a55]
[fv-az1341-704:62020] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb7104a5a6f]
[fv-az1341-704:62020] [ 8] plumed(+0x146dd)[0x55db20be96dd]
[fv-az1341-704:62020] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb71002a1ca]
[fv-az1341-704:62020] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb71002a28b]
[fv-az1341-704:62020] [11] plumed(+0x15365)[0x55db20bea365]
[fv-az1341-704:62020] *** End of error message ***
</pre>
{% endraw %}
