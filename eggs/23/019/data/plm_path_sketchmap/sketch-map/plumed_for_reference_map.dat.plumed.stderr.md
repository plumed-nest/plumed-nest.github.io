**Project ID:** [plumID:23.019]({{ '/' | absolute_url }}eggs/23/019/)  
Stderr for source:  plm_path_sketchmap/sketch-map/plumed_for_reference_map.dat   
Download: [zipped raw stdout](plumed_for_reference_map.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_for_reference_map.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action VSTACK with label mat : no arguments were specificed
[fv-az1440-40:61706] *** Process received signal ***
[fv-az1440-40:61706] Signal: Aborted (6)
[fv-az1440-40:61706] Signal code:  (-6)
[fv-az1440-40:61706] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f92e3245330]
[fv-az1440-40:61706] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f92e329eb2c]
[fv-az1440-40:61706] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f92e324527e]
[fv-az1440-40:61706] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f92e32288ff]
[fv-az1440-40:61706] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f92e36a5ff5]
[fv-az1440-40:61706] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f92e36bb0da]
[fv-az1440-40:61706] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f92e36a5a55]
[fv-az1440-40:61706] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f92e36a5a6f]
[fv-az1440-40:61706] [ 8] plumed(+0x146dd)[0x55c888cb16dd]
[fv-az1440-40:61706] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f92e322a1ca]
[fv-az1440-40:61706] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f92e322a28b]
[fv-az1440-40:61706] [11] plumed(+0x15365)[0x55c888cb2365]
[fv-az1440-40:61706] *** End of error message ***
</pre>
{% endraw %}
