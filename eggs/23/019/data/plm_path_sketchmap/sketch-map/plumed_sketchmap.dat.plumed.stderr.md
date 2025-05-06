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
[fv-az807-718:62636] *** Process received signal ***
[fv-az807-718:62636] Signal: Aborted (6)
[fv-az807-718:62636] Signal code:  (-6)
[fv-az807-718:62636] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb21b045330]
[fv-az807-718:62636] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb21b09eb2c]
[fv-az807-718:62636] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb21b04527e]
[fv-az807-718:62636] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb21b0288ff]
[fv-az807-718:62636] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb21b4a5ff5]
[fv-az807-718:62636] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb21b4bb0da]
[fv-az807-718:62636] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb21b4a5a55]
[fv-az807-718:62636] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb21b4a5a6f]
[fv-az807-718:62636] [ 8] plumed(+0x146dd)[0x55b1ee1d56dd]
[fv-az807-718:62636] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb21b02a1ca]
[fv-az807-718:62636] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb21b02a28b]
[fv-az807-718:62636] [11] plumed(+0x15365)[0x55b1ee1d6365]
[fv-az807-718:62636] *** End of error message ***
</pre>
{% endraw %}
