**Project ID:** [plumID:23.019]({{ '/' | absolute_url }}eggs/23/019/)  
Stderr for source:  plm_path_sketchmap/sketch-map/plumed_sketchmap.dat   
Download: [zipped raw stdout](plumed_sketchmap.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_sketchmap.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action VSTACK with label mat : no arguments were specificed
[fv-az1657-925:07317] *** Process received signal ***
[fv-az1657-925:07317] Signal: Aborted (6)
[fv-az1657-925:07317] Signal code:  (-6)
[fv-az1657-925:07317] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9d03245330]
[fv-az1657-925:07317] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9d0329eb2c]
[fv-az1657-925:07317] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9d0324527e]
[fv-az1657-925:07317] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9d032288ff]
[fv-az1657-925:07317] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9d036a5ff5]
[fv-az1657-925:07317] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9d036bb0da]
[fv-az1657-925:07317] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9d036a5a55]
[fv-az1657-925:07317] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9d036a5a6f]
[fv-az1657-925:07317] [ 8] plumed(+0x146dd)[0x55a41f87e6dd]
[fv-az1657-925:07317] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9d0322a1ca]
[fv-az1657-925:07317] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9d0322a28b]
[fv-az1657-925:07317] [11] plumed(+0x15365)[0x55a41f87f365]
[fv-az1657-925:07317] *** End of error message ***
</pre>
{% endraw %}
