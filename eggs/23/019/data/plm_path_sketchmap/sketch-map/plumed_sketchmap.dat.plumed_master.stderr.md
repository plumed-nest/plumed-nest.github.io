**Project ID:** [plumID:23.019]({{ '/' | absolute_url }}eggs/23/019/)  
Stderr for source:  plm_path_sketchmap/sketch-map/plumed_sketchmap.dat   
Download: [zipped raw stdout](plumed_sketchmap.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_sketchmap.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action VSTACK with label mat : keyword ARG is compulsory for this action
[fv-az1680-626:07580] *** Process received signal ***
[fv-az1680-626:07580] Signal: Aborted (6)
[fv-az1680-626:07580] Signal code:  (-6)
[fv-az1680-626:07580] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f73ecc45330]
[fv-az1680-626:07580] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f73ecc9eb2c]
[fv-az1680-626:07580] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f73ecc4527e]
[fv-az1680-626:07580] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f73ecc288ff]
[fv-az1680-626:07580] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f73ed0a5ff5]
[fv-az1680-626:07580] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f73ed0bb0da]
[fv-az1680-626:07580] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f73ed0a5a55]
[fv-az1680-626:07580] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f73ed0a5a6f]
[fv-az1680-626:07580] [ 8] plumed_master(+0x146dd)[0x55f5cec746dd]
[fv-az1680-626:07580] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f73ecc2a1ca]
[fv-az1680-626:07580] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f73ecc2a28b]
[fv-az1680-626:07580] [11] plumed_master(+0x15365)[0x55f5cec75365]
[fv-az1680-626:07580] *** End of error message ***
</pre>
{% endraw %}
