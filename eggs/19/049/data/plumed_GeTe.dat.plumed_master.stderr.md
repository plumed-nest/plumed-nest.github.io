**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_GeTe.dat   
Download: [zipped raw stdout](plumed_GeTe.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_GeTe.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label cc_cmat : it was not possible to interpret atom name flq6
[runnervmeorf1:11139] *** Process received signal ***
[runnervmeorf1:11139] Signal: Aborted (6)
[runnervmeorf1:11139] Signal code:  (-6)
[runnervmeorf1:11139] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2c2f045330]
[runnervmeorf1:11139] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2c2f09eb2c]
[runnervmeorf1:11139] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2c2f04527e]
[runnervmeorf1:11139] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2c2f0288ff]
[runnervmeorf1:11139] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2c2f4a5ff5]
[runnervmeorf1:11139] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2c2f4bb0da]
[runnervmeorf1:11139] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2c2f4a5a55]
[runnervmeorf1:11139] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2c2f4a5a6f]
[runnervmeorf1:11139] [ 8] plumed_master(+0x146dd)[0x5586ab4346dd]
[runnervmeorf1:11139] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2c2f02a1ca]
[runnervmeorf1:11139] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2c2f02a28b]
[runnervmeorf1:11139] [11] plumed_master(+0x15365)[0x5586ab435365]
[runnervmeorf1:11139] *** End of error message ***
</pre>
{% endraw %}
