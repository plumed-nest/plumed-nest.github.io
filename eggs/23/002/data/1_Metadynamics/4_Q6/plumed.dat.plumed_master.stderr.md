**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/4_Q6/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action LOCAL_AVERAGE with label @s28 : cannot understand the following words from the input line : LOWMEM
[fv-az1680-626:08052] *** Process received signal ***
[fv-az1680-626:08052] Signal: Aborted (6)
[fv-az1680-626:08052] Signal code:  (-6)
[fv-az1680-626:08052] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f174ca45330]
[fv-az1680-626:08052] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f174ca9eb2c]
[fv-az1680-626:08052] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f174ca4527e]
[fv-az1680-626:08052] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f174ca288ff]
[fv-az1680-626:08052] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f174cea5ff5]
[fv-az1680-626:08052] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f174cebb0da]
[fv-az1680-626:08052] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f174cea5a55]
[fv-az1680-626:08052] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f174cea5a6f]
[fv-az1680-626:08052] [ 8] plumed_master(+0x146dd)[0x55c5aaca96dd]
[fv-az1680-626:08052] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f174ca2a1ca]
[fv-az1680-626:08052] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f174ca2a28b]
[fv-az1680-626:08052] [11] plumed_master(+0x15365)[0x55c5aacaa365]
[fv-az1680-626:08052] *** End of error message ***
</pre>
{% endraw %}
