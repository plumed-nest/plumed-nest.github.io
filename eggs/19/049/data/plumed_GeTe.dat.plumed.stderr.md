**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_GeTe.dat   
Download: [zipped raw stdout](plumed_GeTe.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_GeTe.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label cc_cmat : it was not possible to interpret atom name flq6
[runnervmeorf1:11123] *** Process received signal ***
[runnervmeorf1:11123] Signal: Aborted (6)
[runnervmeorf1:11123] Signal code:  (-6)
[runnervmeorf1:11123] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3daa645330]
[runnervmeorf1:11123] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3daa69eb2c]
[runnervmeorf1:11123] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3daa64527e]
[runnervmeorf1:11123] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3daa6288ff]
[runnervmeorf1:11123] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3daaaa5ff5]
[runnervmeorf1:11123] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3daaabb0da]
[runnervmeorf1:11123] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3daaaa5a55]
[runnervmeorf1:11123] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3daaaa5a6f]
[runnervmeorf1:11123] [ 8] plumed(+0x146dd)[0x5583bbb5d6dd]
[runnervmeorf1:11123] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3daa62a1ca]
[runnervmeorf1:11123] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3daa62a28b]
[runnervmeorf1:11123] [11] plumed(+0x15365)[0x5583bbb5e365]
[runnervmeorf1:11123] *** End of error message ***
</pre>
{% endraw %}
