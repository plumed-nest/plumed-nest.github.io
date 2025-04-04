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
[fv-az1680-626:07564] *** Process received signal ***
[fv-az1680-626:07564] Signal: Aborted (6)
[fv-az1680-626:07564] Signal code:  (-6)
[fv-az1680-626:07564] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe0b5045330]
[fv-az1680-626:07564] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe0b509eb2c]
[fv-az1680-626:07564] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe0b504527e]
[fv-az1680-626:07564] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe0b50288ff]
[fv-az1680-626:07564] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe0b54a5ff5]
[fv-az1680-626:07564] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe0b54bb0da]
[fv-az1680-626:07564] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe0b54a5a55]
[fv-az1680-626:07564] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe0b54a5a6f]
[fv-az1680-626:07564] [ 8] plumed(+0x146dd)[0x55f482da96dd]
[fv-az1680-626:07564] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe0b502a1ca]
[fv-az1680-626:07564] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe0b502a28b]
[fv-az1680-626:07564] [11] plumed(+0x15365)[0x55f482daa365]
[fv-az1680-626:07564] *** End of error message ***
</pre>
{% endraw %}
