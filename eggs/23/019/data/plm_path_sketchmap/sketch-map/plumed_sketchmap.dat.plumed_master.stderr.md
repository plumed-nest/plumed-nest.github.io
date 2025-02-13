**Project ID:** [plumID:23.019]({{ '/' | absolute_url }}eggs/23/019/)  
Stderr for source:  plm_path_sketchmap/sketch-map/plumed_sketchmap.dat   
Download: [zipped raw stdout](plumed_sketchmap.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_sketchmap.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action VSTACK with label mat : keyword ARG is compulsory for this action
[fv-az1657-925:07333] *** Process received signal ***
[fv-az1657-925:07333] Signal: Aborted (6)
[fv-az1657-925:07333] Signal code:  (-6)
[fv-az1657-925:07333] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f36ffc45330]
[fv-az1657-925:07333] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f36ffc9eb2c]
[fv-az1657-925:07333] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f36ffc4527e]
[fv-az1657-925:07333] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f36ffc288ff]
[fv-az1657-925:07333] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f37000a5ff5]
[fv-az1657-925:07333] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f37000bb0da]
[fv-az1657-925:07333] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f37000a5a55]
[fv-az1657-925:07333] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f37000a5a6f]
[fv-az1657-925:07333] [ 8] plumed_master(+0x146dd)[0x55b7e6a866dd]
[fv-az1657-925:07333] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f36ffc2a1ca]
[fv-az1657-925:07333] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f36ffc2a28b]
[fv-az1657-925:07333] [11] plumed_master(+0x15365)[0x55b7e6a87365]
[fv-az1657-925:07333] *** End of error message ***
</pre>
{% endraw %}
