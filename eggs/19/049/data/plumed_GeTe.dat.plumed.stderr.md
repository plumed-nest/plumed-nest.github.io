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
[runnervmw9dnm:13537] *** Process received signal ***
[runnervmw9dnm:13537] Signal: Aborted (6)
[runnervmw9dnm:13537] Signal code:  (-6)
[runnervmw9dnm:13537] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fef2c445330]
[runnervmw9dnm:13537] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fef2c49eb2c]
[runnervmw9dnm:13537] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fef2c44527e]
[runnervmw9dnm:13537] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fef2c4288ff]
[runnervmw9dnm:13537] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fef2c8a5ff5]
[runnervmw9dnm:13537] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fef2c8bb0da]
[runnervmw9dnm:13537] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fef2c8a5a55]
[runnervmw9dnm:13537] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fef2c8a5a6f]
[runnervmw9dnm:13537] [ 8] plumed(+0x146dd)[0x55e48a74b6dd]
[runnervmw9dnm:13537] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fef2c42a1ca]
[runnervmw9dnm:13537] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fef2c42a28b]
[runnervmw9dnm:13537] [11] plumed(+0x15365)[0x55e48a74c365]
[runnervmw9dnm:13537] *** End of error message ***
</pre>
{% endraw %}
