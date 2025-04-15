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
[fv-az1370-99:61699] *** Process received signal ***
[fv-az1370-99:61699] Signal: Aborted (6)
[fv-az1370-99:61699] Signal code:  (-6)
[fv-az1370-99:61699] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2acf245330]
[fv-az1370-99:61699] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2acf29eb2c]
[fv-az1370-99:61699] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2acf24527e]
[fv-az1370-99:61699] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2acf2288ff]
[fv-az1370-99:61699] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2acf6a5ff5]
[fv-az1370-99:61699] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2acf6bb0da]
[fv-az1370-99:61699] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2acf6a5a55]
[fv-az1370-99:61699] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2acf6a5a6f]
[fv-az1370-99:61699] [ 8] plumed(+0x146dd)[0x56337f0396dd]
[fv-az1370-99:61699] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2acf22a1ca]
[fv-az1370-99:61699] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2acf22a28b]
[fv-az1370-99:61699] [11] plumed(+0x15365)[0x56337f03a365]
[fv-az1370-99:61699] *** End of error message ***
</pre>
{% endraw %}
