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
[pkrvmf6wy0o8zjz:64259] *** Process received signal ***
[pkrvmf6wy0o8zjz:64259] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:64259] Signal code:  (-6)
[pkrvmf6wy0o8zjz:64259] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb255645330]
[pkrvmf6wy0o8zjz:64259] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb25569eb2c]
[pkrvmf6wy0o8zjz:64259] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb25564527e]
[pkrvmf6wy0o8zjz:64259] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb2556288ff]
[pkrvmf6wy0o8zjz:64259] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb255aa5ff5]
[pkrvmf6wy0o8zjz:64259] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb255abb0da]
[pkrvmf6wy0o8zjz:64259] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb255aa5a55]
[pkrvmf6wy0o8zjz:64259] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb255aa5a6f]
[pkrvmf6wy0o8zjz:64259] [ 8] plumed(+0x146dd)[0x55c172b566dd]
[pkrvmf6wy0o8zjz:64259] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb25562a1ca]
[pkrvmf6wy0o8zjz:64259] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb25562a28b]
[pkrvmf6wy0o8zjz:64259] [11] plumed(+0x15365)[0x55c172b57365]
[pkrvmf6wy0o8zjz:64259] *** End of error message ***
</pre>
{% endraw %}
