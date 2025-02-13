**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_urea.dat   
Download: [zipped raw stdout](plumed_urea.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_urea.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX with label @s41 : missing SWITCH11 keyword
[fv-az1280-696:14069] *** Process received signal ***
[fv-az1280-696:14069] Signal: Aborted (6)
[fv-az1280-696:14069] Signal code:  (-6)
[fv-az1280-696:14069] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5770a45330]
[fv-az1280-696:14069] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5770a9eb2c]
[fv-az1280-696:14069] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5770a4527e]
[fv-az1280-696:14069] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5770a288ff]
[fv-az1280-696:14069] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5770ea5ff5]
[fv-az1280-696:14069] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5770ebb0da]
[fv-az1280-696:14069] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5770ea5a55]
[fv-az1280-696:14069] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5770ea5a6f]
[fv-az1280-696:14069] [ 8] plumed_master(+0x146dd)[0x56140212a6dd]
[fv-az1280-696:14069] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5770a2a1ca]
[fv-az1280-696:14069] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5770a2a28b]
[fv-az1280-696:14069] [11] plumed_master(+0x15365)[0x56140212b365]
[fv-az1280-696:14069] *** End of error message ***
</pre>
{% endraw %}
