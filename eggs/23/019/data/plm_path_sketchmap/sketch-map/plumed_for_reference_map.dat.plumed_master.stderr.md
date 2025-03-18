**Project ID:** [plumID:23.019]({{ '/' | absolute_url }}eggs/23/019/)  
Stderr for source:  plm_path_sketchmap/sketch-map/plumed_for_reference_map.dat   
Download: [zipped raw stdout](plumed_for_reference_map.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_for_reference_map.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action VSTACK with label mat : keyword ARG is compulsory for this action
[fv-az1341-704:62036] *** Process received signal ***
[fv-az1341-704:62036] Signal: Aborted (6)
[fv-az1341-704:62036] Signal code:  (-6)
[fv-az1341-704:62036] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6f46e45330]
[fv-az1341-704:62036] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6f46e9eb2c]
[fv-az1341-704:62036] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6f46e4527e]
[fv-az1341-704:62036] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6f46e288ff]
[fv-az1341-704:62036] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6f472a5ff5]
[fv-az1341-704:62036] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6f472bb0da]
[fv-az1341-704:62036] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6f472a5a55]
[fv-az1341-704:62036] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6f472a5a6f]
[fv-az1341-704:62036] [ 8] plumed_master(+0x146dd)[0x55c7fc6b06dd]
[fv-az1341-704:62036] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6f46e2a1ca]
[fv-az1341-704:62036] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6f46e2a28b]
[fv-az1341-704:62036] [11] plumed_master(+0x15365)[0x55c7fc6b1365]
[fv-az1341-704:62036] *** End of error message ***
</pre>
{% endraw %}
