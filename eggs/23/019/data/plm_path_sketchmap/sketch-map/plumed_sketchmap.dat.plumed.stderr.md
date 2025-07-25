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
[pkrvmpptgkbjq6m:07992] *** Process received signal ***
[pkrvmpptgkbjq6m:07992] Signal: Aborted (6)
[pkrvmpptgkbjq6m:07992] Signal code:  (-6)
[pkrvmpptgkbjq6m:07992] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3890c45330]
[pkrvmpptgkbjq6m:07992] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3890c9eb2c]
[pkrvmpptgkbjq6m:07992] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3890c4527e]
[pkrvmpptgkbjq6m:07992] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3890c288ff]
[pkrvmpptgkbjq6m:07992] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f38910a5ff5]
[pkrvmpptgkbjq6m:07992] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f38910bb0da]
[pkrvmpptgkbjq6m:07992] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f38910a5a55]
[pkrvmpptgkbjq6m:07992] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f38910a5a6f]
[pkrvmpptgkbjq6m:07992] [ 8] plumed(+0x146dd)[0x55ab9ce716dd]
[pkrvmpptgkbjq6m:07992] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3890c2a1ca]
[pkrvmpptgkbjq6m:07992] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3890c2a28b]
[pkrvmpptgkbjq6m:07992] [11] plumed(+0x15365)[0x55ab9ce72365]
[pkrvmpptgkbjq6m:07992] *** End of error message ***
</pre>
{% endraw %}
