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
[fv-az807-718:62560] *** Process received signal ***
[fv-az807-718:62560] Signal: Aborted (6)
[fv-az807-718:62560] Signal code:  (-6)
[fv-az807-718:62560] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7c02a45330]
[fv-az807-718:62560] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7c02a9eb2c]
[fv-az807-718:62560] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7c02a4527e]
[fv-az807-718:62560] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7c02a288ff]
[fv-az807-718:62560] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7c02ea5ff5]
[fv-az807-718:62560] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7c02ebb0da]
[fv-az807-718:62560] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7c02ea5a55]
[fv-az807-718:62560] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7c02ea5a6f]
[fv-az807-718:62560] [ 8] plumed(+0x146dd)[0x557c19cf66dd]
[fv-az807-718:62560] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7c02a2a1ca]
[fv-az807-718:62560] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7c02a2a28b]
[fv-az807-718:62560] [11] plumed(+0x15365)[0x557c19cf7365]
[fv-az807-718:62560] *** End of error message ***
</pre>
{% endraw %}
