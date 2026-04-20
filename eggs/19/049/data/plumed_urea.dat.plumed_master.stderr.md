**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_urea.dat   
Download: [zipped raw stdout](plumed_urea.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_urea.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX with label @s43 : missing SWITCH11 keyword
[runnervmeorf1:11230] *** Process received signal ***
[runnervmeorf1:11230] Signal: Aborted (6)
[runnervmeorf1:11230] Signal code:  (-6)
[runnervmeorf1:11230] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f56cc445330]
[runnervmeorf1:11230] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f56cc49eb2c]
[runnervmeorf1:11230] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f56cc44527e]
[runnervmeorf1:11230] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f56cc4288ff]
[runnervmeorf1:11230] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f56cc8a5ff5]
[runnervmeorf1:11230] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f56cc8bb0da]
[runnervmeorf1:11230] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f56cc8a5a55]
[runnervmeorf1:11230] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f56cc8a5a6f]
[runnervmeorf1:11230] [ 8] plumed_master(+0x146dd)[0x55def23646dd]
[runnervmeorf1:11230] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f56cc42a1ca]
[runnervmeorf1:11230] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f56cc42a28b]
[runnervmeorf1:11230] [11] plumed_master(+0x15365)[0x55def2365365]
[runnervmeorf1:11230] *** End of error message ***
</pre>
{% endraw %}
